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
3. The host picks the mode, **CO-OP vs BANDITS** (team up against AI jets) or **PVP** (fight each other), then taps **START** when everyone is in.

You see each other's jets with name tags (markers at the screen edge point to friends who are out of view), and each other's missiles. It connects players directly using PeerJS, so it needs an internet connection; some strict networks may block it.

## Combat

- **Guns**: hold G (or the GUN button). Aim with the little circle in front of the jet.
- **Missiles**: keep an enemy inside the box until it turns green and says LOCK, then fire (F / right-click / MSL). Locked missiles chase the target; unlocked ones hit the ground where you point.
- **Dodging**: barrel roll (R / click / ROLL) when a missile is close and it loses track of you. Rolling doesn't stop bullets.
- **Warnings**: PULL UP, MISSILE LOCK, incoming MISSILE with its direction and distance, UNDER FIRE, DAMAGE. Turn sound on for warning beeps.
- **Crashing**: once you're flying, nothing pulls you up. Hit the ground or water and you crash, then respawn after a few seconds.
- **Solo**: bandits (red jets) hunt you, shoot and fire missiles. In **multiplayer** you fight each other.

## Controls

**Mouse / keyboard**
- Mouse: steer · Click: barrel roll · Hold click or Shift: afterburner
- G (hold): guns · Right-click or F: missile · R: roll · Space: change view · M: sound · Arrows/WASD: steer

**Phone**
- Drag to steer, or tap **TILT** and lean the phone (left/right to turn, forward/back to dive/climb)
- GUN (hold) · MSL · ROLL · BURN · VIEW buttons
- FULLSCREEN button in the top bar (not available on iPhone)

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
3. The host picks the mode, **CO-OP vs BANDITS** (team up against AI jets) or **PVP** (fight each other), then taps **START** when everyone is in.

You see each other's jets with name tags (markers at the screen edge point to friends who are out of view), and each other's missiles. It connects players directly using PeerJS, so it needs an internet connection; some strict networks may block it.

## Controls

**Mouse / keyboard**
- Mouse: steer · Click: barrel roll · Hold click or Shift: afterburner
- Right-click or F: missile · Space: change view · M: sound · Arrows/WASD: steer

**Phone**
- Drag to steer, or tap **TILT** and lean the phone left/right
- ROLL · BURN · FIRE · VIEW buttons
- FULLSCREEN button in the top bar (not available on iPhone)
