# Mountains Runner: Tail of the Dragon

A mobile-first arcade driving game set on the Tail of the Dragon (US 129, Deals Gap NC into Tennessee): 318 curves in 11 miles.

Open `index.html` in any phone or desktop browser. No build step. The 3D graphics use three.js loaded from the jsDelivr CDN; if it can't load (offline or no WebGL), the game falls back to the built-in classic renderer.

## Features
- Real-time 3D (WebGL): the road is laid out from the same curvature the physics uses, with forest, rock walls, guardrails, distant ridges, sun and shadows, clear-coat car paint with sky reflections, headlights at night, wet-road reflections, fog and bloom. Graphics setting: 3D High, 3D Fast or Classic, with automatic step-down on slow devices
- 16 real cars in three garages, with factory horsepower, weight, 0-60, top speed, gearbox and real paint names:
  - American: Ford Mustang GT, 1970 Dodge Charger R/T 426 Hemi, Dodge Challenger SRT Hellcat Widebody, Chevrolet Corvette Stingray Z51 (C8), 1996 Dodge Viper GTS
  - European: Porsche 911 GT3, BMW M3 (E46), BMW M3 (E30), Volkswagen Golf GTI 16V (Mk2), Lotus Elise S1, Lamborghini Aventador SVJ
  - JDM: Toyota Sprinter Trueno AE86, Nissan Skyline GT-R V-Spec (R34), Toyota Supra Turbo (Mk IV), Mazda RX-7 (FD3S), Mazda MX-5 Miata (NA)
- Realistic driving model: power, aero drag and gearing fitted to each car's real 0-60 and top speed; tire grip shared between braking and cornering (friction circle); no-ABS cars lose steering under hard braking; real road grades
- Engine sound from a physical exhaust model: every cylinder fires in the car's real firing order into a modeled exhaust pipe and muffler, plus turbo whistle and blow-off, supercharger whine and overrun crackle
- Turbo lag and optional anti-lag (bangs and flames off throttle), automatic or manual gears with shift buttons (Q/E on a keyboard), wet roads with rain
- Chase, hood or cockpit camera (working gauges, steering wheel that turns with the front wheels, right-hand drive in the AE86 and R34), button or drag-wheel steering, and a full-sim mode with steering assist turned off
- Two routes: the 3-mile sprint or the full 11-mile Dragon, with a curve counter and mile markers
- Named corners (Copperhead Corner, Gravity Cavity, Shade Tree Corner, Wheelie Hell, Brake or Bust Bend), the Tree of Shame, guardrails, cliffs and October foliage
- Oncoming and same-direction traffic, including motorcycles
- Morning fog, golden hour and night (headlights) modes
- Touch controls (steer, brake, gas, optional auto-gas), plus keyboard: arrows/WASD, Space to brake, P to pause
- Synthesized engine and tire sounds; personal best per car and route saved on the device

## Driving tips
Cornering force grows with the square of your speed. Brake in a straight line before a curve, turn in, and get back on the gas on the way out. The yellow advisory signs show a comfortable speed for each curve; the grip meter next to the speedometer turns orange when the tires are at their limit. Top speed rarely matters here.
