# Strumline

A rhythm trainer for guitar - and a groove trainer for bass - in a single, dependency-free `index.html` you can open in any browser.

This is a hobby project. You can check it out at:

**https://vb1lyi.github.io/strumline/**

## What it does

Use the **Guitar / Bass** toggle in the header to switch instruments.

**Shared**

- Metronome with lookahead-scheduled Web Audio timing
- BPM control (40–240): slider, ±1 buttons, and tap tempo - remembered separately per instrument
- Time signatures 4/4 and 3/4, with quarter-, eighth-, and sixteenth-note subdivisions
- Swing, volume, count-in, and playback toggles
- Loop editing and Focus mode
- Chord trainer with random progressions

**Guitar**

- Strum/skip grid: click any circle to toggle strum (lit) or skip (dash)
- Percussive strum "chk"
- Pattern presets for every subdivision

**Bass**

- Note grid where each dot is a scale degree: **R** (root), **5**, **8** (octave), **3** (third)
- Groove presets (roots on 1 & 3, root–fifth, eighth drive, walking quarters, octave bounce, syncopation, …)
- Editing: click a dot to cycle R → 5 → 8 → 3 → off; click the link between dots to sustain a note; click a held cell to shorten it
- Pitched bass synth (saw + sub-octave through a lowpass)
- Kick/snare/hat drum groove as a time reference
- Articulation (Staccato / Normal / Legato)
- Key + Major/Minor scale, with a live note legend (`E major · R E · 3 G# · 5 B · 8 E`)

## Chord trainer

Open **Chord trainer** to pick chords or roll a random progression. 
The progression drives the bass line's root and quality per bar - a minor 
chord gets a ♭3 - and `Bars per chord` controls how long each lasts. 
While a progression is playing, the Key and Major/Minor controls follow the active chord.

## Presets

The **My presets** row saves the current grid as a named preset in your browser's
local storage - one set per instrument, each remembering its own time signature
and subdivision. Pick one from the list and press **Load**, or **Delete** to
remove it. Tempo is remembered per instrument too, so switching between guitar
and bass keeps each one's BPM.