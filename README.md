# aframe-jsnes
An experiment to run a javascript Nintendo emulator inside of virtual reality with a-frame

Wishlist:
* fix lighting, things look ugly
* fix scale, things are too big
* add more 80's nostalgia esp. to the back wall a la https://sketchfab.com/models/9583c76fa1b74dafaa0b8912a66613f8
* map nes controls to vive / oculus touch
* allow user to choose alternate environment / backgrounds
* allow switching of games from inside of vr using cartridges
* multiplayer online

Credits
- Thanks to JonathanZWhite for the base of https://github.com/JonathanZWhite/bedroom-model which I modified a bit
- JSNES code covered under GNU GENERAL PUBLIC LICENSE (below)
- VR specific adaptation covered under MIT License

****

README from JSNES original repo ([https://github.com/bfirsh/jsnes](https://github.com/bfirsh/jsnes))

JSNES - A JavaScript NES emulator.
=====

Build
-----

To run locally:

    $ docker-compose up

And it'll be available at http://localhost

To build a distribution:

    $ docker-compose run build grunt

This will create ``jsnes.js`` and ``jsnes-min.js`` in ``build/``.

Benchmark
---------

The benchmark in ``test/benchmark.js`` is intended for testing JavaScript
engines. It does not depend on a DOM or Canvas element etc.
