Invaders from... Space!
-----------------------

Pew pew!

[Play](https://invaders-from-space.glitch.me/)

I created this game to explore and practice modern JavaScript. The code is mainly vanilla ES6 style (classes) with no compilation so view-source etc works as [Sir Tim](https://en.wikipedia.org/wiki/Tim_Berners-Lee) intended. 

[Pixi.js](http://www.pixijs.com/) is used for graphics/animation and is the only external dependency. I also used [PWA builder](http://manifoldjs.com/generator) to generate the manifest and service worker for that offline PWA goodness.

Originally a [pen](https://codepen.io/joegaffey/pen/KqgGNE), invaders was moved to [Glitch](https://glitch.com/edit/#!/invaders-from-space) when it needed more room to grow.

The back-end is optional and is turned off in the client by default (usually...WIP). Use the Props.SERVER_AVAILABLE setting to enable. When the backend is enabled there are no invaders initially.
To create one POST any JSON object e.g. {} to:

[http://invaders-from-space.glitch.me/games/{id}/invaders](http://invaders-from-space.glitch.me/games/{id}/invaders) 

GET game ids at:

[http://invaders-from-space.glitch.me/games](http://invaders-from-space.glitch.me/games)

The app requires a modern browser. I test it (a little) in Chrome (Windows, Android), Firefox (Windows) and Edge. Let me know if you find a [bug](https://github.com/joegaffey/invaders/issues)!

Thanks to those linked above and [Classic Gaming](http://www.classicgaming.cc) for the [sound effects](http://www.classicgaming.cc/classics/space-invaders/sounds)!