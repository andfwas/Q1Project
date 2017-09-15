# Q1 Project
Waveform App

## Project Description
A Web-based Synth Pad For Everyone

## What problem does your project
Synthesize sounds from a webpage

## Who has this problem?
- People without synthesizers
- People who aren't experts in sound synthesis or wave visualization
- People without synthesizer software or hardware

## How will your project solve this problem?
Eliminate the need for a hardware or software synthesizers or visualizers

## What inputs does it need?
- Click
- Drag
- Touch

## What web API(s) will it use?
- [Web Audio API](http://blog.teamtreehouse.com/building-a-synthesizer-with-the-web-audio-api)
- [Oblique Strategies](http://brianeno.needsyourhelp.org/)

## What technologies do you plan to use?
- HTML
- CSS
- Bulma
- Javascript
- Firebase

## Feature list
- Produce tones with a waveform generator
- Click or touch a region on the synth pad to produce various sounds
- Change the type of sound to play
  - Select a waveform for generation
- Display a creative strategy on the bottom of the page each time a new waveform is selected

## Upcoming Features
- Frequency range sliders
  - Low frequency limit
  - High frequency limit
  - Low frequency setting cannot be higher than high frequency limit & vice versa
- Waveform select buttons will stay lit and turn off when another waveform is selected
  - This will eliminate the need for the pad background to display the current waveform
    - PadInstructions.png can remain 100% of the time
- Pad images
  - Create PadInstructions.png so that the dark grey fades into a lighter grey simulating wear and tear
- Make all h-tag innerHTML in the main html file appear to be coming from a backlit led display
  - Monochromatic or multi-color?

  <img width="1680" alt="buttonlightone" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/ButtonLightOne.png?raw=true">
  <img width="1680" alt="buttonlighttwo" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/ButtonLightTwo.png?raw=true">
  <img width="723" alt="narrowsaw" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/NarrowSaw.png?raw=true">
  <img width="723" alt="narrowtriangle" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/NarrowTriangle.png?raw=true">
  <img width="723" alt="startnarrow" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/StartNarrow.png?raw=true">
  <img width="1680" alt="startwide" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/StartWide.png?raw=true">
  <img width="742" alt="strategy" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/Strategy.png?raw=true">
  <img width="1680" alt="widesin" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/WideSin.png?raw=true">
  <img width="1680" alt="widesquare" src="https://github.com/andfwas/Q1Project/tree/master/ScreenShots/WideSquare.png?raw=true">


## Upcoming Modifications
- Margins:
  - Space between waveform select buttons and blue glowing gradient in header should be slightly larger
  - Space between "credit" and "deckCard" tags should be larger
  - Space between "credit" and "strategy" tags should be smaller
    - For the above 2 items, make them the opposite of what they are now

## Upcoming Fixes
- stopSound
  - Sometimes stopSound doesn't work & page needs to be refreshed
- Separate functions more effectively
  - Bugs that come from unnecessarily interwoven functionality
    - Fetch from remote servers vs. local processes should be separated
  - Separate js app files if necessary
