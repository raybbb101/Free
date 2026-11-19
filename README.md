# Patrol

A pixel-art fighter jet over a world of nine countries at sunset, in WebGL2. Three camera views, a working cockpit panel, and missiles.

Open `index.html` in a browser to play. Works with GitHub Pages too.

## The world

A 14 km map that wraps around, split into nine countries, each with its own landscape:

- **Autumn woods**: Ambervale, Rustwood. Thick red and gold forests, scattered villages.
- **Farmland**: Millbrook, Wheatmere, Greenhollow. Patchwork fields, hedgerows, red-roofed villages.
- **Ice fields**: Frostmark, Glacia. Snow, frozen lakes, snowy pine forests.
- **Volcanic land**: Ashkarra, Cindral. Smoking volcanoes, lava lakes and rivers of lava.

Forests and villages are real 3D trees and houses when you fly low. Borders show as dashed lines on the ground, and the country name appears when you fly into a new one.

## Solo and multiplayer

The home screen has **SOLO** and **MULTIPLAYER**.

Multiplayer is for 2 to 4 players online:
1. One player taps **HOST A ROOM** and gets a 5-letter code.
2. Friends tap **MULTIPLAYER**, type the code and tap **JOIN**.
3. When everyone is in, the host taps **START**.

You see each other's jets with name tags (markers at the screen edge point to friends who are out of view), and each other's missiles. It connects players directly using PeerJS, so it needs an internet connection; some strict networks may block it.

## Controls

**Mouse / keyboard**
- Mouse: steer · Click: barrel roll · Hold click or Shift: afterburner
- Right-click or F: missile · Space: change view · M: sound · Arrows/WASD: steer

**Phone**
- Drag to steer, or tap **TILT** and lean the phone left/right
- ROLL · BURN · FIRE · VIEW buttons
- FULLSCREEN button in the top bar (not available on iPhone)
