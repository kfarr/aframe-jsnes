# aframe-jsnes
An experiment to run a javascript Nintendo emulator inside of virtual reality with a-frame.

[Try it out here](https://kfarr.github.io/aframe-jsnes/) (warning it takes a while to load all elements.)

<img src="https://kfarr.github.io/aframe-jsnes/assets/aframe-jsnes-screenshot.jpg" />

Wishlist:
* fix lighting, things look super ugly without better lighting. tv should be emitting glow
* fix scale, things are too big
* add more 80's nostalgia esp. to the back wall a la https://sketchfab.com/models/9583c76fa1b74dafaa0b8912a66613f8
* improve overlay UI including a close/hide button
* improve progressive loading experience and order (load black, then static, then tv model, then room, then emulator, then skybox last)
* map nes controls to vive / oculus touch, and/or experiment with xbox controller
* allow user to choose alternate environment / backgrounds
* allow switching of games from inside of vr using cartridges
* multiplayer online

Credits
- based on JSNES, original repo ([https://github.com/bfirsh/jsnes](https://github.com/bfirsh/jsnes))
- Thanks to JonathanZWhite for the base of https://github.com/JonathanZWhite/bedroom-model which I modified a bit
- JSNES code covered under GNU GENERAL PUBLIC LICENSE (see license file)
- VR specific adaptation covered under MIT License
