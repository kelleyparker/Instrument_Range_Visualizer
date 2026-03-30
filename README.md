# Instrument Range Visualizer

An interactive single-page web app for visually comparing the written and sounding pitch ranges of standard band and orchestral instruments.

**Live site:** https://kelleyparker.github.io/Instrument_Range_Visualizer/

---

## Features

- **23 instruments** across four families — Woodwinds, Brass, Strings, and Keyboard/Harp
- **Concert vs. Written pitch toggle** — switch between sounding ranges and written (transposed) ranges; transposing instruments display both simultaneously
- **Sort controls** — sort by instrument family, lowest note, or highest note
- **Hover tooltips** — shows exact range and transposition interval for each instrument
- **Color-coded by family** with a built-in legend
- **Octave grid** from C0 to C8 with half-octave reference lines
- Fully responsive for desktop and mobile
- No external dependencies — vanilla HTML, CSS, and JavaScript

## Instruments Included

| Family | Instruments |
|---|---|
| Woodwind | Piccolo, Flute, Oboe, English Horn, Clarinet (B♭), Bass Clarinet, Alto Sax, Tenor Sax, Bari Sax, Bassoon, Contrabassoon |
| Brass | Trumpet (B♭), French Horn, Trombone, Bass Trombone, Euphonium, Tuba |
| String | Violin, Viola, Cello, Double Bass |
| Keyboard | Piano, Harp |

## Range Reference

All ranges reflect standard professional playable ranges using scientific pitch notation (C4 = middle C). Ranges do not include extended techniques.

Transposing instruments show:
- **Solid bar** — primary range for the selected view (sounding in Concert mode, written in Written mode)
- **Dashed overlay** — the alternate range, showing the transposition offset visually

## Usage

Open `instrument-ranges.html` directly in any modern browser, or visit the live GitHub Pages site linked above.
