# songcraft

Write a song with Claude, even if you have never written a lyric.

Give it a poem, a story told in plain words, or lyrics you already have.
songcraft asks only what is missing (at most five plain questions), offers
three hook lines made from your own words, and writes the full lyric at
once. You then improve it together, round by round: every edit you suggest
is tested against the whole song, and you always get the complete merged
text back, ready to paste.

When the words will be sung, it adds a tool-agnostic arrangement brief
(tempo, metre, key or mode, voice, instruments, dynamic curve, what to
listen for) that works with any music generator or a human composer.
On request it also gives guitar chords, a chord chart for every line,
a strumming pattern and a chorus melody sketch, with the stressed
syllables placed on the melodic peaks.

It works in any language; the melody and stress rules are written in
detail for Turkish.

## Install (Claude Code)

```
/plugin marketplace add cemsari/songcraft
/plugin install songcraft@aixfoundry
```

Then type `/songcraft:songcraft` followed by your idea, for example:
`/songcraft:songcraft a birthday song for my son, cheerful, with chords`

## What it will not do

- It cannot hear audio. It will say so if you ask for the chords of a
  recording, and explain how to extract them with other tools.
- It does not invent facts about real people: anything you did not tell it
  is written as a question or a wish, and new images are labelled as new.

## License

MIT. See LICENSE.
