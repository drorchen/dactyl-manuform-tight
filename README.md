# Dactyl ManuForm Tight Keyboard With A Trackball

This is a fork of the [Dactyl-ManuForm-Tight](https://github.com/okke-formsma/dactyl-manuform-tight). The Dactyl-ManuForm-Tight is a fork of the [Dactyl-ManuForm](https://github.com/tshort/dactyl-keyboard). The Dactyl-Manuform is a fork of the [Dactyl](https://github.com/adereth/dactyl-keyboard) with the thumb cluster from [ManuForm](https://github.com/jeffgran/ManuForm).
The trackball socket is taken from [Qurn's trackball](https://gitlab.com/keyboards1/dm_r_track/-/tree/master).

![Imgur](https://i.imgur.com/wm7Yq1O.jpg)
![Imgur](https://i.imgur.com/fzT6SjV.jpg)
![Imgur](https://i.imgur.com/2P6wJYQ.jpg)

## Problems
- The sensor (PMW3360) is too large to fit in the case, I had to print a bottom plate with it cut out:
![Imgur](https://i.imgur.com/esv2Nww.jpg)
- Due to the increased tenting of the thumb cluster, I had to cut the edges of the keycaps to put them in:
![Imgur](https://i.imgur.com/sQflYZF.jpg)

## Features
- Embedded trackball in the right half of the keyboard.

## Generate OpenSCAD and STL models

* Run `lein repl`
* In the repl run `(load-file "src/dactyl_keyboard/dactyl.clj")`
* This will regenerate the `things/*.scad` files
* Use OpenSCAD to open a `.scad` file.
* Make changes to design, repeat `load-file`, OpenSCAD will watch for changes and rerender.
* When done, use OpenSCAD to export STL files


## Tips

* When trying things out, 10 seconds of rendering time in OpenSCAD is really annoying. Load one of the test outputs with commented out parts that you don't use.
* If you're not sure what things are generted by a piece of code, color them in using something like
`(color [0.5 0.5 0.5 0.5] (the code)`

## License

Copyright © 2015-2022 Matthew Adereth, Tom Short, Leo Lou, Okke Formsma, Qurn, Jup Itzme, Dror Chen.

The source code for generating the models is distributed under the [GNU AFFERO GENERAL PUBLIC LICENSE Version 3](LICENSE).

The generated models are distributed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE-models).
