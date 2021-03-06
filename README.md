# OCaml and SDL 2.0

![OCaml and SDL](
http://openclipart.org/image/250px/svg_to_png/174316/games.png)

## Intro

OCamlSDL2 is an OCaml interface to the SDL2 library.

If you are searching for OCaml bindings for SDL 1.2
then you should go there instead:
  [ocamlsdl.sf.net](
  http://ocamlsdl.sourceforge.net/)

## FAQ

Why another OCaml SDL bindings?

SDL1 was released under the LGPL and OCamlSDL1 too.
(LGPL without any exception on static linking.)
SDL2 is released under a liberal license. And it was
impossible to reach the authors of OCamlSDL1 to ask
them to change the license.
If SDL changes again its license in the future to any
Floss / OSI approved license, you can use these
bindings under the terms of the same license.

## Current State

These relays are currently in a very early draft state.
You may expect to get segfaults.
These pieces of code are currently called "relays"
and not bindings while there is currently no memory
management and no integration with the garbage collector.

## License

This software is provided "AS-IS", without any express
or implied warranty.
In no event will the authors be held liable for any
damages arising from the use of this software.

Permission is granted to anyone to use this software
for any purpose, including commercial applications,
and to alter it and redistribute it freely.

