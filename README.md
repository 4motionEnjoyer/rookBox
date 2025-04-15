rookBox, a small sigint/hacking tool.

The current assembly consists of:
- RPi4 running RaspberryPI OS (debian bullseye)
- Huzzah32 dev board with wifi marauder from justcallmekoko
- Cariboulite SDR with the matteoserva's fork for tx support

To be done:
- Design a case for the system and 3d print it
- Create a python based touchscreen UI with app integration (eg. marauder-uart-gui, more perhaps in the future?)
- EMI shielding for the cariboulite, the system creates noise that the cariboulite picks up.

