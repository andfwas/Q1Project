# Q1 Project Proposal 1
~~Bassic System~~
Waveform App

## Project Description
A website that will synthesize a waveform into audio output.
~~Specifically, it will generate bass tones. The "bass tones" utilized will be frequencies ranging from 18Hz to 120Hz.~~

#### BONUS

## What problem does your project solve?
Synthesize sounds from a webpage

#### BONUS
A website that will listen to sound and create a realtime rapidly updated graphic representation of the sound.

## Who has this problem?
People without synthesizers

#### BONUS
People without software or hardware to visualize sound.
Deaf people.

## How will your project solve this problem?
Eliminate the need for a hardware or software synthesizer

#### BONUS
Eliminate the need to purchase gear or software that does this.

## What inputs does it need?
Click and drag

#### BONUS
- Microphone
- Line

## What outputs does it produce?
Sound

#### BONUS
2D animated graph

## What web API(s) will it use?
[Web Audio API](http://blog.teamtreehouse.com/building-a-synthesizer-with-the-web-audio-api)
[Oblique Strategies](http://brianeno.needsyourhelp.org/)

#### BONUS
[AnalyserNode API](https://developer.mozilla.org/en-US/docs/Web/API/AnalyserNode)

## What technologies do you plan to use?
- HTML
- CSS
- ~~Bootstrap~~
- Bulma
- Javascript
- Firebase

## Feature list
- Produce~~bass~~ tones with a waveform generator
- Click or touch a region on the screen to produce various sounds
- Change the type of sound to play
  - Choose wave type from a drop-down menu
  - Create your own waveform
    - Draw a waveform?
    - Manipulate existing preset waveform?
- Save sounds or "patches"
  - Export to audio file
  - Save or download audio file
  - Send audio file via email

- Explain
  - real world usage
  - how and why
    - link to subtractive synthesis?


#### BONUS
- Show a graph of any sound
  - Use mic for input
    - Voice
    - Musical instruments
    - Any sound or noise
  - Use line input
    - Media player device
    - Native app analysis
      - Quicktime
      - Spotify
      - iTunes
- Choose options to control what you are seeing
  - Frequency range
  - Volume range
  - Waveform view
  - Spectrum view
  - Graph update speeds (refresh rate)
    - Faster (uses more resources)
    - Slower (uses less resources)

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
