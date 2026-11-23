# Patrol

A pixel-art fighter jet over a world of nine countries at sunset, in WebGL2. Three camera views, a working cockpit panel, and missiles.

Open `index.html` in a browser to play. Works with GitHub Pages too.

**Install it like an app**: on the home screen tap **⬇ INSTALL GAME** (Chrome/Android/PC), or use Chrome's menu → *Install app*. On iPhone: Safari → Share → *Add to Home Screen*. The installed game opens fullscreen in landscape and works offline (multiplayer still needs internet).

## The world

A 14 km map that wraps around, split into nine countries, each with its own landscape:

- **Autumn woods**: Ambervale, Rustwood. Thick red and gold forests, scattered villages.
- **Farmland**: Millbrook, Wheatmere, Greenhollow. Patchwork fields, hedgerows, red-roofed villages.
- **Ice fields**: Frostmark, Glacia. Snow, frozen lakes, snowy pine forests.
- **Volcanic land**: Ashkarra, Cindral. Smoking volcanoes, lava lakes and rivers of lava.

Forests and villages are real 3D trees and houses when you fly low. Borders show as dashed lines on the ground, and the country name appears when you fly into a new one.

**Game controller** (e.g. GameSir X5 Lite, or any standard Xbox-layout pad)
- Plug it in and press any button: the game switches to controller mode and hides all the touch buttons. Touch the screen to go back to phone controls. You can also force it on the home screen with **CONTROLS: AUTO / CONTROLLER / PHONE**.
- Left stick or D-pad: steer (left/right turn, up/down climb/dive)
- RT or X (hold): guns · RB or B: missile · LB or A: barrel roll · LT (hold): afterburner · Y: change view
- Menus: stick / D-pad to move, A to press, B to go back. In the repair mini game, the stick moves a cursor and A presses.

## Solo and multiplayer

The home screen has **SOLO** and **MULTIPLAYER**.

Multiplayer is for 2 to 4 players online:
1. One player taps **HOST A ROOM** and gets a 5-letter code.
2. Friends tap **MULTIPLAYER**, type the code and tap **JOIN**.
3. The host picks the mode, **CO-OP vs BANDITS** (team up against AI jets) or **PVP** (fight each other), then taps **START** when everyone is in.

**Lives and stages (multiplayer)**
- Everyone has **3 lives**. Lose them all and you get one chance to **fix your jet**: a short repair mini game (tighten bolts, reconnect wires or pump the pressure gauge, two picked at random). Finish it to fly again with 1 life. Lose that too and you're out.
- **CO-OP** has 3 stages: 3, 5, then 7 tougher bandits. Bandits don't come back once shot down. Clear a stage to move on; every new stage gives everyone 3 lives again. If the whole team is out, the stage restarts.
- **PVP**: last pilot still flying wins the round, then a new round starts.

You see each other's jets with name tags (markers at the screen edge point to friends who are out of view), and each other's missiles. It connects players directly using PeerJS, so it needs an internet connection; some strict networks may block it.

## Combat

- **Guns**: hold G (or the GUN button). Aim with the little circle in front of the jet.
- **Missiles**: keep an enemy inside the box until it turns green and says LOCK, then fire (F / right-click / MSL). Locked missiles chase the target; unlocked ones hit the ground where you point.
- **Dodging**: barrel roll (R / click / ROLL) when a missile is close and it loses track of you. Rolling doesn't stop bullets.
- **Warnings**: PULL UP, MISSILE LOCK, incoming MISSILE with its direction and distance, UNDER FIRE, DAMAGE. Turn sound on for warning beeps.
- **Crashing**: once you're flying, nothing pulls you up. Hit the ground or water and you crash, then respawn after a few seconds.
- **Solo**: bandits (red jets) hunt you, shoot and fire missiles. In **multiplayer** you fight each other.

## Rings and balloons

- **Gold rings** float all over the map. Fly through one for a 4-second speed boost. Boosts stack: fly through 2 or 3 close together for an even bigger burst. A used ring turns grey for a few seconds.
- **Balloons** float around too. Touch one to pop it and slow the enemies down for 5 seconds (bandits in solo and co-op, the other pilots in PVP). Popped balloons come back after a while.

## Controls

**Mouse / keyboard**
- Mouse: steer · Click: barrel roll · Hold click or Shift: afterburner
- G (hold): guns · Right-click or F: missile · R: roll · Space: change view · M: sound · Arrows/WASD: steer

**Phone**
- **Left thumb stick**: touch anywhere on the left half of the screen and drag (left/right = turn, up/down = climb/dive). Or tap **TILT** and lean the phone instead
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
