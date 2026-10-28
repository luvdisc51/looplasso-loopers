# Looplasso Loopers

> **In development (indev).** This game is a work in progress. Things will change and break.

A browser game where your real glowing string loop is the controller. Befriend 285 Loopers by sending the string through them or looping it around them. Unofficial fan game, not affiliated with Loop Labs.

- Pick your string color (RGB, red, green or blue) so the camera can find it.
- Optionally teach the game your lasso's sound. It pauses when you switch the lasso off and resumes when you switch it on.
- A Looperdex tracks which of the 285 Loopers you have befriended.

## Running it

The camera and microphone need a secure page. Open the link on your phone.

Also see [Looplasso Loopers 360](../looplasso-loopers-360/), the VR / 360 version. The Looperdex is shared between the two when both are served from the same address.

## How capturing works

- Your Looplasso makes a ring of light with a hole in the middle. A Looper has to go **through the hole**: swing the ring so the Looper ends up inside it. Lift the ring off and do it again for the next point of progress.
- The camera tracks the **whole string**, not just one spot. It fits a circle to the lit string to find the hole, so it works with thin, dim, far away, blown-out or partly hidden strings. Brightness thresholds adjust on their own. On the setup screen, tap your string to lock the color to exactly what the camera sees.
- It ignores the rest of your house: solid blobs (lamps, screens, clothes), stray pieces far from the string and anything that stays lit in the same spot for about 10 seconds are dropped. It also learns your room whenever the lasso is off, and you can tap **Hide my room** on the setup screen (with the lasso off) to teach it on purpose. In touch mode, draw a full loop around it with your finger.
- A Looper's heart flashes open now and then. Going through while it is open gives bonus points and extra time.
- Passes close together build a combo (up to x5). Bubbles that hit your string snap it and break the combo.
- Every mission you finish makes the next Loopers a bit faster.

## Inventory

Every Looper you befriend pays you coins on the spot (more for rarer ones) and goes into your **Inventory**, with a count if you catch the same one again. There is nothing to sell by hand. The Looperdex still tracks which of the 285 you have met.

## Birthday Looper

The first time you play, the game asks for your birthday (month and day only, kept on your device). On your birthday, Birthdeeoo, Looper #285, visits as the first Looper of your mission. It is skipped when the game counts "meet every Looper" for the legendary Kaleidon (#284).

## Install as an app (PWA)

Open the page over https, then use "Add to Home Screen" (iPhone and Android) or the install button in Chrome. It runs full screen and works offline after the first visit. Icons are in `icons/`.

## Coins and worlds

- Threads, loops and befriending Loopers earn coins (more with a combo). Coins are saved on your device.
- Spend coins on **Worlds** in the menu. There are six: Mossy Meadow (free), Glimmer Caves, Ember Dunes, Frostbite Peaks, Stormcloud Isles and Starfall Void.
- Each world has its own Loopers. The Loopers in later worlds need more loops (x1 up to x3.5) and get a bit more time.
- The legendary Kaleidon appears in any world once you have met every other Looper.

## About

The menu has an **About** tab with the version, the authors and your browser (plus a few details about your device).
