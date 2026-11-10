# Veda Book Index

Machine-readable back-of-book indexes for Vedic and Indo-Iranian research literature.

## Source data

The `index-locorum/` directory preserves the source TSV files from [Yuzki/rigveda/reference](https://github.com/Yuzki/rigveda/tree/main/reference). Each nonempty TSV records a textual corpus abbreviation, passage identifier, and page/footnote reference in a scholarly book. Entries are transcriptions and may contain irregular punctuation, ranges and abbreviated references; they are not validated normalized records.

| File | Source |
| --- | --- |
| Delbruck_Syntax.tsv | Berthold Delbrück, *Altindische Syntax* |
| Goto_IPrasens.tsv | Toshifumi Gotō, *Die „I. Präsensklasse“ im Vedischen* |
| Goto_Morphology.tsv | Toshifumi Gotō, *Old Indo-Aryan Morphology and Its Indo-Iranian Background* |
| Hoffmann_Injunktiv.tsv | Karl Hoffmann, *Der Injunktiv im Veda* |
| Narten_SigmatischenAortiste.tsv | Johanna Narten, *Die sigmatischen Aoriste im Veda* |

`Jamison_ayaSuffix.tsv` is a zero-byte placeholder in the source repository, not an index dataset; it is preserved separately in `placeholders/`.

## Principles

- Retain original transcription and source file attribution.
- Treat page references as **pointers to discussions**, not evidence of what an author argues.
- Normalize identifiers only in derived layers, retaining each source row.
- Verify transcription accuracy, publication details, and data reuse conditions before public distribution or downstream authoritative use.

## Related integration

[Veda AI issue #116](https://github.com/Yuzki/veda-ai/issues/116) tracks using the indexes for scholarly evidence discovery.
