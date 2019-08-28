## Compass (v1.0)

__Compass__ is a sequencer-based asynchronous looper for Monome Norns. Plug in a mono or stereo source, and then use Compass' built-in sequencer to manipulate recording and looping behaviors. A few commands are also available to manipulate the sequence itself. 

__*Input Routing & Recording*__

Once the script is loaded, head to Norns' `params` menu to select your input source type (mono or stereo). If using a mono source, be sure to plug it into the left input. Set proper monitoring in the `system/audio` settings as well. By default, __Compass__ records your audio source into two 64s buffers: one for each voice. 

__*Sequencing*__

__Compass'__ audio buffers and its sequencer each have their own sense of time in order to facilitate experimentation. Use the command row on the `EDIT` page to, for example:

- create wild timing fluctuations in your sequence
- dynamically change your loop length
- push the two records heads to different positions in your loop or sync them back up. 
- alter the rate and direction of each record head

__*Keys & Encoders*__

- `E1` : Scroll between the `EDIT` and `REFERENCE` pages
- `E2` : Navigate to step in command row
- `E3` : Select command at step
- `K2` (short) : reset command row to default state (does *not* affect softcut buffers)
- `K2` (long): randomize all commands
- `K3` (short) : toggle recording on/off
- `K3` (long): clear both softcut buffers (does *not* affect command row)
