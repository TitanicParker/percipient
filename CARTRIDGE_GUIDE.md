# Structuracy — Console cartridge guide

Place `index.html` and `cartridge.md` in the root of a GitHub Pages repository. The game automatically reads `cartridge.md` when served over HTTP(S). You can also choose any compatible `.md` cartridge using **LOAD A .MD CARTRIDGE**. Local `file://` browsing may block the automatic fetch, but the file picker still works.

## Cartridge format

A Markdown file containing one fenced `json` block:

```json
{
  "format": "structuracy-cartridge-v1",
  "title": "My sentence cartridge",
  "language": "en",
  "sentences": [
    {"id": "s1", "cell": 1, "text": "Now I can tell which one it is."},
    {"id": "s2", "cell": 2, "text": "The difference shows up in how these two compare."}
  ]
}
```

`id` is optional but useful for traceability. Each `cell` must be an integer 1–54. A cartridge is an authored answer key; the console does not independently classify sentences. The two-sentence mode requires at least two different cells that vary on exactly one of the three axes. With good coverage, it will cycle through every eligible cell-pair type rather than always drawing from the same cells. The one-sentence mode can run with a single sentence.

The console intentionally keeps technical labels hidden from players. The first playable edition uses concise automated everyday paraphrases for answer choices. Later, reviewed and more subtle choices can replace them without changing the cartridge data model. The single-sentence mode's automatic alternatives are a working baseline, not a sentence-specific editorial judgment about the nearest plausible rival.

For a public GitHub Pages repo, all committed source files are publicly accessible, even those not displayed in the interface. Keep proprietary research files in a separate private repo if confidentiality is required.
