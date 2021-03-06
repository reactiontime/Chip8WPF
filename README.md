Chip8WPF
========

I have always been interested in emulators, they always seemed like magic to me. I wrote this as a first step towards learning emulation programming.

It's currently pretty basic, but it does support save states and should run all the roms that exist in the wild. One nice feature via WPF is the ability to resize the screen and the rendering will adapt to it and maintain its aspect ratio. I couldn't find any info regarding the beep noise the system plays, so I created a small wave file to use so the emulator wouldn't be silent. This may or may not have been a good idea.

It should be easy to extract the core code and Chip8Emulator.cs if you're interested in changing the windowing/rendering system.

![Alt text](/screenshots/brix.png "BRIX")

![Alt text](/screenshots/pong.png "PONG2")

![Alt text](/screenshots/tetris.png "TETRIS")

Resources I used to develop this:
* [Wikipedia](http://en.wikipedia.org/wiki/Chip8)
* [Mastering CHIP-8](http://mattmik.com/chip8.html)
