# Looplasso Loopers

> **In development (indev).** This game is a work in progress. Things will change and break.

A browser game where your real glowing string loop is the controller. Befriend 51 Loopers by looping the string around them. Unofficial fan game, not affiliated with Loop Labs.

- Pick your string color (RGB, red, green or blue) so the camera can find it.
- Optionally teach the game your lasso's sound. It pauses when you switch the lasso off and resumes when you switch it on.
- A Looperdex tracks which of the 51 Loopers you have befriended.

## Running it

The camera and microphone need a secure page. Turn on GitHub Pages for this repo (Settings, Pages, deploy from the main branch) and open the link on your phone.

Also see [Looplasso Loopers 360](../looplasso-loopers-360/), the VR / 360 version. The Looperdex is shared between the two when both are served from the same address.

## How capturing works now

- **Thread it:** sweep your glowing string straight through a Looper. Its heart flashes open now and then. Passing through an open heart gives a full hit and a little extra time. A closed heart gives half.
- **Or circle it:** a full loop around a Looper still counts.
- Threads and loops close together build a combo (up to x5). Bubbles that hit your line snap it and break the combo.
- Every mission you finish makes the next Loopers a bit faster.

## Install as an app (PWA)

Open the page over https, then use "Add to Home Screen" (iPhone and Android) or the install button in Chrome. It runs full screen and works offline after the first visit. Icons are in `icons/`.
