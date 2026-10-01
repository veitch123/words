# Words

The word list for the **Words** iPhone app and widget. The app reads
[`words.txt`](words.txt) from this repository.

## Adding a word

Edit `words.txt` (the pencil icon on GitHub works fine, including on the phone):
the word on its own line, its meaning on the line underneath, the word used in
a sentence on a line starting with `>`, and a blank line before the next word.
Tap the widget to see the sentence.

```
Saudade (noun)
A deep, wistful longing for someone or something you love that is absent, and may never return.
> Hearing the old song brought back a wave of saudade for the summers they spent by the sea.

Petrichor (noun)
The earthy smell after rain falls on dry ground.
> The first drops hit the hot pavement and the air filled with petrichor.
```

The sentence is optional; a word without one simply doesn't turn over.

`Word: meaning` on a single line works too.

The widget picks up changes at its next hourly refresh; opening the app (or
pulling down on its list) fetches them straight away.
