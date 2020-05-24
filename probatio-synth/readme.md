Probatio Synth for Max
======================

John Sullian, IDMIL. February 2020

http://idmil.org
http://probat.io

## ABOUT: 

A simple 2-oscillator subtractive synthesizer and step sequencer designed for use with the Probatio v1.0 system and Libmapper (via Webmapper). 

## TO USE: 

- **Max**: Ensure you have Max installed on your computer. 
- **Libmapper**: ensure you have libmapper binaries for Max installed and in your Max Search Path. Ensure you have Webmapper installed and set up properly.  
- Open _**probatio_synth.maxpat**_, making sure the accompanying Max files are preserved in the patcher's root directory.
- Check that Probatio is on and discoverable on same network. 
- Configure your connections from Probatio to synth using Webmapper.

Input Scaling options (top of patch): by default, the patch opens in "Probatio" mode, where 8-bit probatio output data is internally scaled to the appropriate synth input ranges. MIDI mode dees the same but accepts 7-bit values. "None" bypasses all scaling and you will have to do your own mapping conversions in Webmapper. 

## Continued Work: 

- double click on [p todos-and-future-work] subpatcher.

