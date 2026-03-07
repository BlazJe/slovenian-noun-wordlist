# Slovenian Noun Wordlist

A plain-text list of **43,501 Slovenian common nouns** (one per line), extracted from the [Sloleks 3.1](https://viri.cjvt.si/sloleks/) morphological lexicon.

## Contents

- `besede.txt` — one lemma (dictionary form) per line, UTF-8 encoded

## Filtering criteria

Only entries matching all of the following were included:

- **Part of speech:** noun
- **Type:** common (proper nouns and named entities excluded)

## Source

Extracted from **Sloleks 3.1** — the Slovenian morphological lexicon developed by the [Centre for Language Resources and Technologies (CJVT)](https://www.cjvt.si) at the University of Ljubljana.

> Sloleks is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). This derived wordlist is shared under the same license.

## Usage

```python
with open("besede.txt", encoding="utf-8") as f:
    words = [line.strip() for line in f if line.strip()]
```
