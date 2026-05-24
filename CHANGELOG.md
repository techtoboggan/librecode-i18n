# Changelog

Format: [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) · [SemVer](https://semver.org/).

## [0.9.33] — 2026-05-25

### Changed

- **`session.tab.activity` value**: `"Activity"` → `"Timeline"`. The
  internal tab identifier is unchanged; only the user-facing label
  moves. Pairs with main-repo Phase 46.

## [1.0.0-preview.1] — 2026-04-15

Aligns with LibreCode main repo v1.0.0-preview.1.

### Added
- **`desktop/th.ts`** — Thai (ภาษาไทย) locale file for the desktop app
  (menus, dialogs, updater, CLI installer, loading, server). Matches the
  31-key coverage of `desktop/en.ts`.
- **`desktop/tr.ts`** — Turkish (Türkçe) locale file, same coverage.
- Both locales exported from `src/desktop/index.ts`.

### Changed
- Bumped to `1.0.0-preview.1` to align with main LibreCode repo.

## [0.1.0] — Initial release

- `app/`: 17 locales (ar, br, bs, da, de, en, es, fr, ja, ko, no, pl, ru, th, tr, zh, zht)
- `ui/`: same 17 locales
- `desktop/`: 15 locales (missing th, tr — added in 1.0.0-preview.1)
