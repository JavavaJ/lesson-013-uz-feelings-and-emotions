## Uzbek — Lesson 003: Feelings and Emotions

A small, focused module for learning Uzbek vocabulary and expressions related to feelings and emotions. This repository is intended to be part of a series of compact, self-contained lessons.

### Goals
- Build a clean dataset of common emotion-related words and phrases in Uzbek
- Provide clear English translations and example sentences
- (Planned) Add audio pronunciations and simple practice activities

### Repository Structure
The repo starts minimal. Suggested structure as content is added:

- `data/` — Source data (CSV/JSON) for vocabulary, phrases, example sentences
- `audio/` — Optional audio files (e.g., MP3/WAV) for pronunciation
- `notebooks/` — Exploration, prototyping, or annotation notebooks
- `scripts/` — Utilities for converting, validating, or exporting content
- `app/` — Optional small UI (web or CLI) to browse/search the content

### Getting Started
Right now this repo contains documentation only. As data/scripts land, typical workflows will look like:

1. Create the suggested folders you plan to use (e.g., `data/`, `scripts/`).
2. Add your vocabulary list (CSV/JSON) to `data/`.
3. (Optional) Add audio files to `audio/` with consistent naming tied to entries in `data/`.
4. (Optional) Add scripts to `scripts/` for tasks like export, validation, or flashcard generation.

### Data Format (suggestion)
If using CSV for vocabulary, a simple schema works well:

```csv
id,uzbek,english,part_of_speech,example_uz,example_en,notes,audio
001,xursand,glad; happy,adj,"Bugun men xursandman.","I am happy today.",,"audio/001.mp3"
```

### Roadmap
- [ ] Add initial vocabulary dataset (feelings/emotions)
- [ ] Add example sentences with translations
- [ ] (Optional) Add audio files and link them in `data/`
- [ ] Add a simple script to export Anki/CSV flashcards
- [ ] (Optional) Add a tiny web viewer for browsing/search

### Contributing
Issues and pull requests are welcome. Keep the scope of this lesson small and focused. If you want to propose broader changes, consider opening a discussion first.

### License
TBD. If you have a preference (e.g., MIT), add a `LICENSE` file and update this section.
