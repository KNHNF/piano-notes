# Piano Notes

A free, single-file piano practice tool. Open `index.html` in any browser; no install, no account, works offline.

## Features

- Write a two-hand sheet in plain text (`R:` and `L:` lines, bars separated by `|`, `-` rest, `~` hold)
- Rendered as a proper grand staff (treble and bass clefs, note heads, stems, ledger lines, bar lines, accidentals)
- Selectable time signature (4/4, 3/4, 2/4, 6/8) shown on the staff
- Automatic finger number suggestions (1 to 5) printed above the treble and below the bass staff
- Playback with the current note highlighted on the staff and on the on-screen keyboard
- Six synthesised instrument sounds (warm grand, upright, bright, electric, music box, organ)
- Save sheets in the browser, download as a file, load a file back in
- MusicXML import: scan paper sheet music with [Audiveris](https://github.com/Audiveris/audiveris) (free, open source), export as uncompressed MusicXML (.xml / .musicxml), and load it with the Load file button
- Clickable keyboard and computer-key input for quick note finding

## Sheet format

```
R: C4 D4 E4 F4 | G4 F4 E4 D4 | C4 E4 G4 C5 | C5 ~ - -
L: C3 - G3 -   | C3 - G3 -   | C3 - E3 G3  | C3 ~ - -
```

Note names are letter, optional `#` or `b`, octave (`C4` is middle C). `-` is a rest, `~` extends the previous note by one beat.

## Roadmap

- MIDI file import
- Multiple staff lines instead of one scrolling system

## Licence

MIT
