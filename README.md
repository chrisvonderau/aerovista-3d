# AeroVista 3D

A Grand Tour competitive flight game — and the original Scenic Tour — over six regions: the Swiss Alps, Grand Canyon, Mount Everest, the Norwegian Fjords, Yosemite, and the Cascades.

Open it here: [chrisvonderau.github.io/aerovista-3d](https://chrisvonderau.github.io/aerovista-3d/)

This is a single offline HTML file. It does not need a network connection after you have the file, so it also works from Mail or Files.

## Play

Choose a mode on the title screen. **Easy** is the default and includes auto-level assist. **Normal** and **Ace** tighten the courses.

### Grand Tour

Six events, one in each region, about two minutes each (around 12 minutes for a standard run):

1. **Matterhorn Circuit** (Swiss Alps) — ring race. Missed rings add a time penalty; a ring chain grants a speed boost.
2. **Rim to River** (Grand Canyon) — fly low through gates. Hitting terrain recovers you (it is not game over) but costs time; staying low scores an altitude bonus.
3. **Khumbu Chain** (Mount Everest) — a second, tighter ring race.
4. **Bridge & Barn** (Norwegian Fjords) — limited bombs, shared cartoon targets (barns, bridges, haystacks, the odd sheep). Hitting hikers costs points.
5. **Valley Chase** (Yosemite) — Sky Tag. In 2P the chaser tags inside a radius and roles swap; survival time scores for the evader. In 1P you chase (and are chased by) an AI drone.
6. **Volcano Hayfields** (Cascade Range) — a second bomb run over Cascade meadows.

Events convert to tour points: **1st place 10**, **2nd place 6** (a tie is 8). In 1P you are scored against par and your best (a ghost of your record run appears when you have one). A small bonus (up to 4) is added for clean or stylish play. Standings appear between events; a champion screen with fanfare and confetti closes the tour. Best totals and event bests are saved in the browser.

- **1 Player** — race your best scores and ghost.
- **2P Split-Screen** — two planes, two viewports (side by side on wide screens, stacked in portrait). Quality is lowered automatically and the pixel ratio is capped.
- **2P Take Turns** — pass-and-play with a “Player 2, get ready” handoff.

A 3-second countdown and an on-screen goal line start every event.

### Scenic Tour

The original free-flight sightseeing mode is still on the menu: autopilot landmarks, four cameras, a cockpit HUD, optional Sky Rings, and optional bombing runs.

### Controls

- **Keyboard P1:** WASD to steer and climb or dive, Space to drop a bomb. In Scenic Tour, arrows also steer, and B or F also bombs.
- **Keyboard P2:** arrow keys to fly, Enter to bomb.
- **Xbox:** A confirms and can start a 1P tour from the menu. Each pad flies one plane in split-screen (any controller index, even if they are not 0 and 1). Left stick steers, LT/RT or stick Y climb and dive, X drops a bomb, Y opens the Tour Director, Menu toggles Cinema Mode. Rumble fires on rings, hits, and tags.
- **Touch (1P or take-turns):** a left-hand stick plus the bottom-right BOMB button. The Scenic Tour still lets you tap the terrain or radar to divert.

- **Restart:** hold R or Backspace (keyboard) or View/Back on an Xbox pad for about 0.7 seconds to restart the current event. A short hold keeps it from firing by accident. In split-screen both players must hold (P2 uses Shift or View).
- **Invert Pitch:** a per-player (P1/P2) toggle in the Tour Director and the Grand Tour setup. It is saved and applies to the stick, keys, and touch.
- **Stick sensitivity:** Low, Normal, or High, with a fixed deadzone.
- **Reduce Motion:** turns off speed/dive FOV widening and the micro camera shake on bomb blasts and near-misses.

The version mark **v5.1** is visible in the location pill. Pull to refresh if you still see an older version.

## Version history

### v5.1

Off-screen chevrons point to the next ring, gate, target, or tag opponent when it leaves the view (per viewport in split-screen). Split-screen now has a mini HUD in each viewport. Ghost split deltas compare each ring, gate, or target against your best run (green if you are ahead, red if behind). Invert Pitch and stick sensitivity are saved per browser. Biome particles (snow in the Alps and Everest, dust in the Canyon, mist in the Fjords) scale with the High/Med/Low quality tiers and are off in split-screen. Normal and Ace add stunt and near-miss multipliers; Easy stays forgiving. Reduce Motion disables the subtle FOV widening and camera shake.

### v5

Grand Tour competitive mode (1P, 2P split-screen, 2P take-turns), six mixed events, standings and a champion screen, saved bests and ghosts, Easy/Normal/Ace, and the Scenic Tour kept as its own menu option. Still a single offline file.

### v4.2

Sky Rings with combo scoring, a cockpit avionics HUD, wingtip contrails and a twilight landing light, a Help modal, baked radar terrain, and a compact dock so Help and Cinema both fit on iPhone 390-wide screens.

### v4.1.1

On iPhone, the BOMB control is a large round button at the bottom-right thumb position.

### v4.1

Optional bombing runs with an aiming reticle, cooldown, and pooled FX. People and animals are never harmed.

### v4

Offline single file, Xbox and keyboard control, Quality settings, Cinema Mode, and leak-free region switching.
