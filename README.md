# ChapterCast

Open-source **podcast + audiobook** player for Android — a community fork of [AntennaPod] built to add **first-class audiobooks** while staying true to AntennaPod’s privacy and openness.

> **License:** GPL-3.0-only • **Status:** Active development (alpha) • **Min SDK:** 23 • **Toolchain:** Kotlin, JDK 17, AGP • **Playback:** Media3/ExoPlayer

[![Android CI](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/android-ci.yml/badge.svg)](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/android-ci.yml)
[![CodeQL](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/codeql.yml/badge.svg)](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/codeql.yml)
[![Dependency Review](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/<YOUR_HANDLE>/ChapterCast/actions/workflows/dependency-review.yml)

---

## Why ChapterCast?

- **Podcasts + Audiobooks in one** app  
- **Local library via SAF** (add folders, persist permissions)  
- **Chapters, bookmarks, per-book progress** (planned)  
- **Mixed-media queue**: episodes + books (planned)  
- **Accessibility & i18n**: TalkBack, large text, RTL, WCAG AA

We keep AntennaPod’s values and add features **additively** (no regressions, DB add-only).

---

## Project status

- Phase 1: module scaffolding & indexing (in progress)  
- Phase 2: chapters/bookmarks/progress  
- Phase 3: mixed queue & polish

Roadmap lives in [#Roadmap](docs/ROADMAP.md) and GitHub Milestones.

---

## Build

- **Android Studio (latest stable)**, JDK 17
- `./gradlew assembleDebug`  
- CI treats warnings as errors (detekt, ktlint, Spotless, Android Lint)

See [CONTRIBUTING.md](CONTRIBUTING.md) for dev setup.

---

## Community

- Ask questions in **Discussions**  
- File bugs with the **Bug** template  
- Propose features with the **Feature** template

Please read the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Credits & attribution

- **Fork of [AntennaPod]** (GPLv3). Not affiliated with the upstream project.  
- Media playback by **AndroidX Media3/ExoPlayer**.

---

## License

GPL-3.0-only. See [LICENSE](LICENSE).

[AntennaPod]: https://github.com/AntennaPod/AntennaPod
