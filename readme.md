# a1c4i1d
This is the code for the song I uploaded to Bandcamp, and the synth settings file.
https://hirokimatsui.bandcamp.com/track/a1c4i1d

I used TidalCycles (https://tidalcycles.org/) to sequence the rhythm while controlling a Korg Minilogue XD and an Elektron Monomachine.

Each orbit of TidalCycles was multi-out and recorded using Bitwig Studio. Post-processing such as compressor and reverb was applied, but the recording was done in real time, just like Livecoding.

## mlxd_setup.tidal
Define variables to control Minilogue XD. 141.tidal accesses Minilogue's MIDI CC with the name of the variable defined here.

## a1c4i1d.tidal
This file is the code for the song. I'm using Minilogue XD's VCO1 as Bass, VCO2 as Melody, and Multi Engine as Bell. By controlling the volume of these three oscillators in different patterns, I was able to get a polyphonic sound. The Multi Engine used as the Bell is set to bypass the VCF in the main unit settings.
