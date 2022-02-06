# Dactyl ManuForm Tight Keyboard With A Trackball

This is a fork of the [Dactyl-ManuForm-Tight](https://github.com/okke-formsma/dactyl-manuform-tight). The Dactyl-ManuForm-Tight is a fork of the [Dactyl-ManuForm](https://github.com/tshort/dactyl-keyboard). The Dactyl-Manuform is a fork of the [Dactyl](https://github.com/adereth/dactyl-keyboard) with the thumb cluster from [ManuForm](https://github.com/jeffgran/ManuForm).
The trackball socket is taken from [Qurn's trackball](https://gitlab.com/keyboards1/dm_r_track/-/tree/master).
I used parts of the [Derek Nheiley's code](https://github.com/dereknheiley/dactyl-manuform-tight).
The hotswap is taken from [ibnuda's code](https://github.com/ibnuda/dactyl-keyboard/tree/hotswap).

![Imgur](https://i.imgur.com/wm7Yq1O.jpg)
![Imgur](https://i.imgur.com/fzT6SjV.jpg)
![Imgur](https://i.imgur.com/2P6wJYQ.jpg)

## Problems
- The sensor (PMW3360) is too large to fit in the case, I had to print a bottom plate with it cut out, and attach anti-slipping stickers to raise the keyboard higher from the desk:
![Imgur](https://i.imgur.com/esv2Nww.jpg)
- Due to the increased tenting of the thumb cluster, I had to cut the edges of the keycaps to put them in:
![Imgur](https://i.imgur.com/sQflYZF.jpg)

## Firmware
I'm using [Noah Prince's fork of QMK](https://github.com/noahprince22/qmk_firmware/tree/trackball).

## Features
- Embedded trackball in the right half of the keyboard.
- Hotswap sockets.
- Increased tenting.

## License

Copyright © 2015-2022 Matthew Adereth, Tom Short, Leo Lou, Okke Formsma, Qurn, Jup Itzme, Derek Nheiley, ibnuda, Dror Chen.

The source code for generating the models is distributed under the [GNU AFFERO GENERAL PUBLIC LICENSE Version 3](LICENSE).

The generated models are distributed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE-models).
