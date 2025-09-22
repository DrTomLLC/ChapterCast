# Contributing to ChapterCast

Thanks for helping! This project follows **additive development**:
- No regressions to existing AntennaPod behaviors.
- Database: **add new tables/columns only**; never break migrations.

## Dev setup
- Android Studio (latest), JDK 17
- Kotlin only for app code; optional Rust for FFI (behind flags)
- Run locally: `./gradlew spotlessApply detekt ktlintCheck assembleDebug test`

## Style & quality gates
- **ktlint** + **Spotless** (formatting)
- **detekt** (treat warnings as errors)
- **Android Lint** (fatal)
- **No blocking on main thread**; coroutines + structured concurrency
- **Sealed results**; exhaustive `when`; null-safety first

## Commit & PR guidelines
- Use Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`, etc.)
- One topic per PR; include tests where feasible
- Link issues with `Fixes #123`
- All PRs must pass CI and be reviewed

## Security
See [SECURITY.md](SECURITY.md). Report privately first.

## Legal
- **GPL-3.0-only**; all contributions must be GPL-compatible
- No proprietary SDKs, DRM, or scraping
