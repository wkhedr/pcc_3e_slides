# English PPT Translation Workspace

This directory is reserved for English translated PowerPoint decks.

The original Chinese PowerPoint files remain in `../PPT/`.

Planned output structure:

```text
PPT_EN/
├── chapter1.pptx
├── chapter2.pptx
├── ...
└── chapter20.pptx
```

Translation guidelines:

1. Preserve the original slide order, visual structure, diagrams, animations, and code formatting.
2. Translate Chinese instructional text into clear academic English suitable for classroom use.
3. Keep Python code, commands, filenames, keywords, and identifiers unchanged unless a Chinese explanatory comment needs translation.
4. Keep attribution to the original author and preserve the CC BY-NC-SA 4.0 licensing terms.
5. Treat Chapter 1 as the validation deck before translating all remaining chapters.

Status:

- `README_EN.md` has been added at the repository root.
- PPTX translation is pending because the current GitHub connector exposes text-file editing reliably, but does not expose large binary PPTX files in a way that can be safely round-tripped here without data loss.
