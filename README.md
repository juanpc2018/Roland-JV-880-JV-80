# Roland-JV-880-JV-80
https://www.vintagesynth.com/roland/jv-880 </br>

Problem #1. </br>
This synth depends on the DATA Rotary Encoder,
becomes useless if rotary encoder gets damaged.</br>
unless you have a software like MIDIQuest Editor Librarian.</br>
https://squest.com/Products/MidiQuest13/Instruments/RolandJV-880/</br>
to change sounds manually is complicated </br>
https://support.roland.com/hc/en-us/articles/201921759-JV-80-JV-880-Choosing-Sounds-from-MIDI</br>

Problem #2.</br>
Data Encoder stops working IF cr2032 battery die, </br>
Firmware Bug "Feature".</br>

Problem #3.</br>
Data Encoder has No replacement, its a rare type No longer manufactured...</br>

JV-880 Data Encoder its physically compatible with modern KY-040 encoders, but electric signals are incompatible.</br>

Sollutions:</br>
#1.</br>
Replace rotary encoder with 3 micro switches:</br>
Left Push Right.</br>
this is the cheapest & energy efficient sollution.</br>

#2. </br>
Replace Rotary Encoder with KY-040, use old PCB.</br>
modification options required:</br>
A) add a circuit with cmos logic 40 / 70</br>
B) add a micro controller or fpga to convert signals</br>
PIC, Arduino, Atmel, Propeller, Upduino, etc...</br>

The original rotary encoder has OR logic.</br>
The KY-040 encoders has +/-45° phase shift, similar to Timecode DVS Vinyl records.</br>

P.D.</br>
There was someone selling programable expansion cards, JV-880 can only hold one on the top cover.</br>

JV-880 has 2 different DAC chips, for MainOut 1&2, and Aux1&2.</br>

