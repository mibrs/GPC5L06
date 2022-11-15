Short introduction

![MIDI Recording](midi-recording.png)

MIDI is a protocol for musical instruments and related devices to communicate. [This link](https://www.youtube.com/embed/sziykFl44CU) brings you to a short introductory video what you can do with it.

All information consist out of 7 bit numbers, so there are 128 different values between 0 and 127. 

The protocol allows to send the following information:

Pitch - tone, Ex.: middle C (or C3) has the value 60
Velocity - loud/low voice, volume
Program - instrument
Device identifier - if you have several MIDI devices
By sending messages with the above information to a MIDI instrument, you can play music.

![MIDI Data](Logic2-4252846884.jpeg)

The diagram below shows pitch and program for values between 35 and 81. The keyboard is split in half as it would have been too long otherwise to display properly. As an example. 60 as pitch would play the middle C note, 60 as program plays Hi Bongo as an instrument. Program/instrument 0 is the default instrument and sounds like a grand piano.

![Codes for MIDI Instruments](2021-12-13_16-13-08.png)

The Wikipedia entry [here](https://en.wikipedia.org/wiki/MIDI) has more materials about the MIDI protocol.
