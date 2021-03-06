# Tape Drive

![Do not insert Duct Tape.](block:computronics:computronics.tapeReader)

The tape drive is a block that allows for playback and recording of audio data. [Cassette tapes](../item/tape.md) can be placed into the tape drive and come in durations of 2 to 128 minutes. Note that the tape drive isn't restricted purely to audio data - other types of data can be written to the [cassette](../item/tape.md).

Due to the low filesize, Audio is recorded in the DFPWM format. Converting from MP3 or other common audio formats is tricky; however, it is possible to convert from WAV files to DFPWM using a program called [LionRay](http://wiki.vex.tty.sh/wiki:computronics:tape#lionray). The converted audio file can then be written, byte-by-byte, to the cassette tape. More detailed information on DFPWM can be found [on the wiki](http://wiki.vex.tty.sh/dfpwm).

The tape drive also has a `seek()` function, allowing fast-forwarding to a specific point on the [cassette tape](../item/tape.md). Providing a negative value to the `seek()` rewinds the [cassette tape](../item/tape.md) to an earlier point. 

The tape drive provides a program called `tape` which allows for convenient reading, writing and playing of tapes.
