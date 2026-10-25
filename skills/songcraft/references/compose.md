# Composition layer: chords and melody sketch

Use this file only when the user asked for chords, a melody, or "beste"
(at intake or later). Otherwise give no chord chart and no melody notes;
the key named in the arrangement brief is fine.

## 1. Pick the harmonic approach from the song's register

Decide this before writing any chord. The register comes from §3 of
SKILL.md and the user's reference ("like X").

| Register | Approach | Palette and moves |
|---|---|---|
| Makam-heavy, tasavvuf, uzun hava | Drone, not progression | Tonic pedal or open fifths; at most one or two chord changes per section. Leave koma notes to the voice; never put a tempered third under them. |
| Arabesk, fantezi | Minor home, modal colour | i, iv, v, ♭VI, ♭VII. Prefer minor v to major V. Rest on a half-step descent: ♭VI→v (F→Em, stays in La minör) or ♭II→i (B♭→Am, Kürdî: La Si♭ Do Re Mi Fa Sol). Hicaz instead lands on a MAJOR tonic from ♭II (B♭→A; La Si♭ Do# Re Mi Fa Sol, augmented second Si♭–Do#). |
| Turkish pop | Minor home, short loops | Loops of 3–4 chords from i, iv, v, ♭III, ♭VI, ♭VII. The Western four-chord loop (I–V–vi–IV) is rare in Turkish songs; use it only if the user wants a Western sound, and say so. |
| Anadolu rock, rock | Modal riffs | ♭VII–i and ♭II–i endings; IV often leads home instead of V; power chords suit makam melodies because they have no third. |
| Türkü (popular arrangement) | Pedal plus few changes | Tonic pedal; i–♭VII–i; one change per line at most. |
| Rap, trap, EDM-pop | Loop under groove | One or two minor chords repeated; harmony serves the beat. |
| Western ballad, jazz-tinged | Functional | ii–V–I, secondary dominants; maj7 and add9 for nostalgia. |

If the song mixes registers, pick the one the chorus belongs to and say
the verse may be barer.

## 2. Output contract (all parts, in this order)

1. **Key and capo:** key in plain words ("La minör"), and which capo fret
   moves it into a typical male or female range.
2. **Chord shapes:** each chord once, with a guitar fingering (x02210).
   Offer an easier shape for any barre chord.
3. **Chord chart:** every section, every lyric line, bars marked
   `| Am | Am |`. Chord changes fall on line or half-line boundaries.
4. **How to play:** one strumming or arpeggio pattern per section, and
   where the guitar stops.
5. **Chorus melody sketch:** one note name per syllable (Do Re Mi), the
   stressed syllables in bold, the highest note marked. Verses: describe
   the range only.
6. **One alternative:** a simpler or a fresher chorus progression, one line,
   with what it changes.
7. **Why these chords:** two or three bullets tied to the register table.

## 3. Melody rules for Turkish words

Turkish shows stress mainly with pitch, less with the beat. So:

- **Stressed syllable → melodic peak or long note.** Regular final stress
  is weak; it may fall on a weak beat. Exceptional stress is strong and
  sounds wrong when buried. Protect these:
  - the syllable before a negative -mA: GEL-me-di, o-TUR-ma-sın, BİT-me-sin;
  - the syllable right before question mI and clitics dA, ki, -cA, -lA:
    gel-Dİ mi, SEN de;
  - the syllable before an ek-fiil after a noun or a tense:
    has-TAY-dı, ya-PAR-dın, kal-KAR-dın, gi-DER-se;
  - the first vowel of -Iyor, -ArAk, -IncA: kal-KI-yor-sun, ge-Lİ-yor,
    gö-RÜN-ce (-IncA after a consonant stem);
  - person endings after a tense or a noun (-Im, -sIn, -Iz, -sInIz):
    ya-PAR-sın, u-zak-TA-yım, ge-Lİ-rim;
  - fixed-stress words: AN-ka-ra, AN-ne, ŞİM-di, YA-rın, NE-re-de,
    SON-ra, ÖN-ce, BU-ra-da (BUR-da), Bİ-ri, HER-kes, KİM-se, and the
    first part of compounds.
  - Same spelling, different stress changes the meaning: bağla-MA (the
    instrument) vs BAĞ-la-ma (don't tie). Put the melodic peak on the
    reading you mean.
  - If a word is not covered here, say the stress is your guess.
- **Held notes:** on open syllables; a and e carry best. On high held notes
  avoid ü and ö; i and u survive; ı is untested, treat it like ü on the
  highest note. On a closed syllable (gel, yar), hold the
  vowel and put the consonant at the end.
- **Melisma (arabesk, fantezi):** keep the line body one note per syllable;
  put melisma on the rhyme or redif word at the line end, and in a
  free-time intro or outro.
- **Range:** chorus within one octave; verses lower, chorus higher; the
  highest note on the hook's key word.
- **Fit to chords:** every note on a strong beat is a chord tone or a
  tension you meant (7th, 9th). Check each bar.

## 4. Self-check before showing

- Every stressed syllable in the chorus sits on a peak or a long note;
  list any exception and why.
- No ü or ö on a high held note.
- Each chord fits the register row you chose; no unasked Western loop.
- Write the scale of each section (e.g. La Kürdî: La Si♭ Do Re Mi Fa Sol).
  Every chord tone and melody note belongs to it. If one section uses both
  forms of a note (Si and Si♭, e.g. Em next to B♭), either change a chord
  or tell the user it is a deliberate colour change.
- Strong-beat melody notes fit their chords.
- Melody sketch syllable count equals the lyric's.

## 5. Chords of an existing recording

You cannot hear audio. Say so. A chord-recognition app or an open-source
pipeline (stem separation, then audio-to-MIDI) can extract chords or the
vocal line; results are drafts, weaker on makam and koma notes, and must be
checked by ear. If you can run tools on the user's machine, offer to.
