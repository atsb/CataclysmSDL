# A Homeworld Emergence (cataclysm) reverse engineer.

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/7db8aef5-5ed9-4195-92b6-8fc2b1601078" />

## For the Glory of Kiith Somtaaw

I started this a long time ago, around the time I did my Hiigara port of Homeworld and preceeding me joining the GoK team.  In-light of recent revelations of incomplete, half-baked reverse engineer attempts from certain members of the Homeworld community, I feel it is in the best interest to release mine.  Which is complete, correct and fully playable.

## Getting started

Download the windows package and drop it into your Homeworld Cataclysm or Emergence directory.

## Features

* Fully 64bit clean
* Original scaling at any resolution (I called it the 'Somtaaw Universal Scaling System')
* Bloom, Soft Particles, Dynamic Lighting, Colour Saturation, Deeper blacks, increased ship and object LOD and view distance
* SDL3 OpenGL Rendering (with Vulkan and Metal renderers planned)
* Skirmish and Single Player fully playable
* Antialiasing, filtering, fullscreen and windowed modes
* Fully uncapped framerate with v-sync targeting the native refresh of the users' display
* Modernised and optimised renderer
* OpenAL for sound/music
* Full bink video playback support
* All 32bit assembler rewritten to perfect C representations (as what I did for the Garden of Kadesh port as well)

I am just finishing a few little touches and it will be released.

## Source code

Source code will NOT be provided (and never will be).  So don't ask.
Why?  Because in this day and age, folks don't want to 'contribute' to projects, they want to throw things to an LLM and call it a day.  I refuse to release the code for that reason, so nobody can take it, chuck it to an LLM to do something else and split the community again (as what has happened with the pointless Homeworld RTX hack) where they took a lot of what Gardens of Kadesh did.  I refuse to allow that, to happen to Cataclysm.  You want the source?  Reverse engineer it yourself.

The binary will also be built from an intentionally obfuscated source tree with functions renamed and code onelined to ensure the binary is exceptionally hard to RE.

## When?

It'll drop soon.
