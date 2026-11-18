# combos

Yu-Gi-Oh! combos transcribed from YouTube videos, one folder per deck.

```
<Deck>/
  <combo>.md                 Obsidian note: summary, decklist, every combo as a Helios-style schema
  pdf/<combo>.pdf            the same note as PDF
  txt/<combo>_N.helios.txt   combo code for the Helios combo trainer (Combos → Import), one per combo
  json/<combo>_N.helios.json the same combo, readable
cards/                       card images (from YGOPRODeck), shared by all decks
```

Every combo is played in the real Helios engine before it is saved: the steps are recorded with
Helios' own combo recorder and then replayed by the trainer's Auto-play on several shuffles.
A combo marked `(partial)` stops where the line of the video could not be reproduced in the engine.
