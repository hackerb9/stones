# stones

## Most useful files

* [stones.abc](/src/stones.abc) The source file for generating the
  sheetmusic and playable sound files.
* [stones.pdf](../../raw/master/objects/stones.pdf) The sheet music.
* [stones-karaoke.mid](../../raw/master/objects/stones-karaoke.mid) A
  MIDI file, including lyrics, that can be used for karaoke. 
* [stones-karaoke.wav](../../raw/master/objects/stones-karaoke.wav)
  PCM audio file generated from MIDI.
* [stones-karaoke.ogg](../../raw/master/objects/stones-karaoke.ogg)
  Compressed audio file generated from WAV.

## About

The video game *Ultima V* comes with a printed *Book of Lore* that
includes a section on the music of its fictional land, Britannia, and
includes an example song, *Stones*. The style appears to be Medieval
"square notation" with a four line staff (𝄙), a Gregorian C Clef (𝇐),
and odd note shapes, such as PORRECTUS (𝇙).

![The Book of Lore: Music](../../raw/master/README.md.d/The%20Book%20of%20Lore:%20Music.jpg "Stones in pseudo-Medieval square notation")

Just for fun, I transcribed the music to ABC format. From that I
created sheet music for the song in both the treble clef (𝄞), which
most people are familiar with, and the Gregorian C clef (𝇐) used in
the book. The sheetmusic include the lyrics for all four verses,
although I did have to adjust them slightly where there were simply
too many syllables. (This might be a sign that I got the transcription
of the music wrong.)

## Transcription halfway (notes but not durations)

𝇐 +C Clef+

𝇕AB 𝆸̅c 𝇕dc 𝆸̅B 𝇕cB 𝆸̅A 𝇙BAG 𝆺E

𝄒 +breath mark+

𝇕AB 𝆸̅c 𝇕Bc 𝆸̅d 𝇕cd 𝆺e•

𝇁 +Longa perfecta rest+

(*custos* at end of staff to foreshadow 'A' on next line.)

𝇐 +C Clef+

𝇕AB 𝆸̅c 𝇕dc 𝆸̅B 𝇕cB 𝆸̅A 𝇙BAG 𝆺E

𝄒 +breath mark+

𝇕AB 𝆸̅c 𝇕dc 𝆸̅b 𝇕AG𝇙BAB  𝆺|A|•

Key: 

Capital letters are one octave lower.

𝆸̅ an *episema* over a *brevis* quarter note (*episema* means hold a little longer)

• means there is a dot after the note (1 beat longer)

|| means there are vertical bars around the note


## If Britannian Music was Square Notation? (Hint: It's not.)

If I understand correctly, *longa* (𝆷), a square with a stem attach
and looks like our quarter note (𝅘𝅥), should be equal to a half note or
a dotted half note depending on the context. (It has something to do
with dividing by threes that I definitely do *not* understand).

But, let's pretend a *longa* is exactly a half note.

A *brevis* (𝆸), half as long as a *longa*, would be a quarter
note (𝅘𝅥)

A *semibrevis* (𝆺), half as long as a *brevis* (𝆸), would be an eighth
note (𝅘𝅥𝅮). 

Although they don't appear in this piece, a *maxima* (𝆶) is twice as
long as a *longa* (𝆷) and would be a whole note (𝅝), while a *minima*
(𝆺𝅥) is half as long as a a semibrevis (𝆺) and thus a sixteenth note (𝅘𝅥𝅯).

Any note with a *episema* line over it is held a little longer.

A dot after a note means it is held one full beat longer.


## Britannian Music is not Square Notation.

Whie the score appears to be Medieval, I think this score is more
similar to our modern music notation for these reasons:

* The Medieval *clivis* (𝇕) represented a single syllable sung as two
notes, but if that was the case here, the lyrics would have way too
many syllables. Treating *clivis* as beamed eighth notes (♫), on the
other hand, matches perfectly.

* The durations of the notes doesn't sound right. The diamond that
looks like a whole note to us (𝅝) is actually a *semibrevis* (𝆺), the
Medieval eighth note. It doesn't make sense that this tune's final
note would be a dotted eighth!

* Also, why are there no longas (𝆷)? And why would every brevis (𝆸)
have an episema line over it (𝆸̅)?

* Stacked notes that would be hard for a modern person to read, such
as PODATUS (𝇔), are absent.

## Interpretation as Medieval square notation

𝇕 *Clivis* (two quarter notes)

𝆸 *Brevis* (quarter note)

𝇙 *Porrectus* (three slurred quarter notes)

𝆺 *Semi-brevis* (eighth note)


## Brittanian notation

My guess at the actual note durations that seems to work and fits
(mostly) within 4/4 measures:

*Clivis* 𝇕 → ♫ Beamed eighth notes

*Brevis* with *episema* 𝆸̅ → 𝅘𝅥 Quarter note

*Porrectus* 𝇙 → Beamed triplet (three eighth notes played in the time of two)

*Semi-brevis* 𝆺 → 𝅗𝅥 Half note

*Dotted Semi-brevis* 𝆺• → 𝅗𝅥𝅭 Dotted half note


## Appendices
A. [Handy Unicode characters for Medieval square notation](README.md.d/medieval.md)
A. [Handy Unicode characters for music in general](README.md.d/musical.md)

A. [Page from 'The Book of Lore: Music'](../../raw/master/README.md.d/The%20Book%20of%20Lore:%20Music.jpg "Copyright 1988 Lord British & Origin")



