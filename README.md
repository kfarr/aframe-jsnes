# aframe-jsnes
An experiment to run a javascript Nintendo emulator inside of virtual reality with a-frame

Wishlist:
* add tv
* add background
* era appropriate 80's background such as https://sketchfab.com/models/9583c76fa1b74dafaa0b8912a66613f8
* map nes controls to vive / oculus touch
* allow user to choose alternate environment / backgrounds
* allow switching of games from inside of vr using cartridges
* multiplayer online

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
