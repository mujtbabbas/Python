# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/TheAlgorithms/Python>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream link, base version provenance, and credit.
- Added this changelog (ENHANCEMENTS.md).
- Added .markdownlint.json and .github/workflows/markdown-check.yml (markdown linting automation for the README and documentation; upstream's build.yml, ruff.yml, ty.yml and Sphinx workflows already run the real test/lint suite and are kept as-is, so no additional code CI was needed).
- Added .editorconfig (standard editor settings, with a 4-space indent section for Python sources; upstream ships none).
- Set repository About: detailed description stating the enhancements and versions; homepage set to the main upstream repository.
- Upstream already ships .github/dependabot.yml (github-actions only, daily, 7-day cooldown) — verified and kept exactly as-is rather than replaced.

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of TheAlgorithms/Python at upstream commit 6e03a48579ca212a08b36be00378f887dc41a003 (upstream HEAD dated 2026-10-19).
- Fork history severed; all 1737 tracked files and the MIT licence (LICENSE.md) preserved as-is, including the 13 binary image/data files (largest data_compression/image_data/PSNR-example-base.png, 4515013 bytes). The two large word lists (strings/words.txt, 2493109 bytes; strings/anagrams.txt, 1366719 bytes) are plain text.
- File-count note: at 1737 baseline files (1741 after the v1.1.0 enhancements) this is the largest Tier 1 repo and sits under, but close to, the 2000-file connector snapshot limit — recorded in the preparation log.
- Line-ending note: 78 upstream files are stored with CRLF line endings under upstream's `* text=auto` .gitattributes; they are preserved byte-for-byte in this baseline (the .gitattributes file itself is also preserved unchanged).
