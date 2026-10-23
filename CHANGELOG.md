# Changelog

All notable changes to this standalone edition of TheAlgorithms/Python are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the README and documentation; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's existing `build.yml`, `ruff.yml`, `ty.yml` and Sphinx workflows run the real test/lint suite and were kept as-is, so no additional code CI was needed.
- Added `.editorconfig` (standard editor settings, with a 4-space indent section for Python sources; upstream ships none).
- Set the repository About description and homepage (the main upstream repository).
- Upstream already ships `.github/dependabot.yml` (GitHub Actions only, daily, 7-day cooldown) — verified and kept exactly as-is rather than replaced.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) at upstream commit `6e03a48579ca212a08b36be00378f887dc41a003` (upstream HEAD dated 2026-10-19).
- Fork history severed; all 1,737 tracked files and the MIT licence (`LICENSE.md`) preserved as-is, including the 13 binary image/data files. The 78 upstream files stored with CRLF line endings were preserved byte-for-byte.
