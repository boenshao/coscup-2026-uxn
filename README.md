# COSCUP 2026 - UXN, A Computer at Human Scale

View the slides in [presenterm](https://github.com/mfontanini/presenterm).

```sh
presenterm SLIDES.md
```

## Demo

Compile [uxn2](https://git.sr.ht/~rabbits/uxn2) (requires SDL2).

```sh
cc $(sdl2-config --cflags) uxn2.c -o uxn2 $(sdl2-config --libs)
```

Assemble the demo with [drifblim](https://git.sr.ht/~rabbits/drifblim).

```sh
./uxn2 roms/drifblim.rom draw-with-keyboard.tal draw-with-keyboard.rom
./uxn2 draw-with-keyboard.rom
```

Try out some ROMs.

```sh
./uxn2 roms/worm.rom    # a snake game
./uxn2 roms/tet.rom     # a tetris game
./uxn2 roms/left.rom    # a text editor
./uxn2 roms/cccc.rom    # a graphical calculator
./uxn2 roms/potato.rom  # an operating system
```

## Learning

* [The UXN Project](https://100r.co/site/uxn.html)
* [Awesome UXN](https://git.sr.ht/~rabbits/uxn)
* [Learn Uxntal in Y minutes](https://learnxinyminutes.com/uxntal)
* [UXN Tutorial by Compudanzas](https://compudanzas.net/uxn_tutorial.html)
* [Reference Implementation - uxn2](https://git.sr.ht/~rabbits/uxn2)

## Documentation

* [Uxntal](https://wiki.xxiivv.com/site/uxntal.html) - Uxntal language reference manual.
* [Varvara](https://wiki.xxiivv.com/site/varvara.html) - Technical documentation of the Varvara computer and a list of all its devices.
* [Opcodes](https://wiki.xxiivv.com/site/uxntal_reference.html) - List of Uxntal opcodes and their effects.

## Talks

* ["An approach to computing and sustainability inspired from permaculture" by Devine Lu Linvega](https://youtu.be/T3u7bGgVspM?si=UHGMbG37CZswNqMw)
* ["Weathering Software Winter" by Devine Lu Linvega](https://youtu.be/9TJuOwy4aGA?si=d_1pD9nMtbKh89mt)
* ["Concatenative programming and stack-based languages" by Douglas Creager](https://youtu.be/umSuLpjFUf8?si=tgrzybEHU8b8u3vM)

## Attributions

CC BY-NC-SA 4.0, https://100r.co/LICENSE.by-nc-sa-4.0.md

* images/rabbits2.png
* images/uxn.png

CC BY-NC-SA 4.0, https://wiki.xxiivv.com/site/about.html#license

* images/uxn.crew.png
* images/uxn.beet.png
* images/uxn.team.png
* images/varvara.uxn.png

MIT License, https://git.sr.ht/~rabbits/uxn2/tree/main/item/LICENSE

* uxn2.c

ISC License, https://git.sr.ht/~rabbits/drifblim/tree/main/item/LICENSE

* roms/drifblim.rom

MIT License, https://github.com/origedit/worm/blob/main/license

* roms/worm.rom

Apache License 2.0, https://github.com/nf/fourtette/blob/main/LICENSE

* roms/tet.rom

MIT License, https://git.sr.ht/~rabbits/cccc/tree/main/item/LICENSE

* roms/cccc.rom

MIT License, https://git.sr.ht/~rabbits/left/tree/main/item/LICENSE

* roms/left.rom

ISC License, https://git.sr.ht/~rabbits/potato/tree/main/item/LICENSE

* roms/potato.rom

CC0, https://compudanzas.net/uxn_tutorial_day_3.html

* draw-with-keyboard.tal

## License

Except as otherwise noted, the content of this repository is licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
