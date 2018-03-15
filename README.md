# step-sequencer
Second part of the Pure Data Theremin development. Now with a step sequencer

You must run the Main.pd patch.

Control features of this step-sequencer include:
• BPM control – also providing TAP TEMPO (i.e. set the tempo by periodically
hitting a given key of the keyboard).
• A separate pitch control for each step (can be a “number box” as in the
example), with a limited pitch range (of your choice).
• Global volume.
• ON/OFF.
• Mute button (the sequencer advances without sounding).
• Transpose (number or slider). Choose the range.
• Randomize button (generates 16 random pitches within the correct range).
Check the [random] object for that.
• Provide several keyboard keys for additional control (at least: start, stop,
pause, randomize, transpose UP and transpose DOWN).
