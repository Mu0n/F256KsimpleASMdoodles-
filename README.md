# F256KsimpleASMdoodles
A collection of small assembly experiments for the F256Jr/K from Foenix Retro Systems

## Foenix Retro Systems
Website: https://c256foenix.com/

Foenix Retro Systems is a homebrew effort to bring 8/16/32-bit era processors in a new, reimagined retro series of computer designed by Stefany Allaire (https://twitter.com/StefanyAllaire)

## ASM 'simple doodles'
These simple examples in 65c02 compatible assembly are my first steps into discovering the machine and its graphic, sound and input capabilities.

To run these, simply copy them over (probably using an SD card) and load them with `/- 'program name.bas'`. I'm assuming you have a recent enough version of pexec.bin in your flash firmware. A good place to start would be to fetch at least release 2023.5 from this github repository: https://github.com/FoenixRetro/f256-firmware/ 

## Hello World in text mode

Should write a simple text message in the first line of text on screen, over whatever was being displayed right before executing.

### Files that are expected in the same directory:

* `helloworld.pgz`