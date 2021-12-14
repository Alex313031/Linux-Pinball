# Linux-Pinball
Builds of https://github.com/k4zmu2a/SpaceCadetPinball for Linux (x64) with files they cant include like the .mid files for sound.

Includes the .mid, .wav, and .dat files along with icons and a .desktop file. The Icon line in the .desktop file can be edited to point to Icon_48x48.png.

Requires libsdl2-dev and timidity to be installed. 

Simply unpack and run the .desktop file, or run ./SpaceCadetPinball, and enjoy!

## Building

Requires libsdl2-dev, libsdl2-mixer-dev, libudev-dev, and timididy to be installed.

Clone this repo, (the bin dir has the extra stuff already in it), cd to the dir, run `cmake .` then `make` That's it!
