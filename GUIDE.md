# Reader's Guide — Python (The Algorithms)

## What this project is

This is **The Algorithms — Python**: a large collection of algorithms
implemented in Python **for education**. Every algorithm is written to be read
and learned from rather than to beat the standard library on speed — the
implementations favour clarity, and most carry explanations, doctests and
references. If you want to understand how an algorithm actually works, this is
the place to read it in Python.

## How the content is organised

Everything is grouped into **one folder per topic** at the repository root,
with the implementations as plain `.py` files inside. The main topic areas:

- **Core CS:** `sorts`, `searches`, `data_structures`, `graphs`,
  `dynamic_programming`, `backtracking`, `divide_and_conquer`,
  `greedy_methods`, `strings`, `bit_manipulation`, `boolean_algebra`.
- **Maths & science:** `maths`, `geometry`, `linear_algebra`, `matrix`,
  `physics`, `electronics`, `geodesy`, `fractals`, `cellular_automata`.
- **Applied:** `machine_learning`, `neural_network`, `computer_vision`,
  `digital_image_processing`, `data_compression`, `ciphers`, `hashes`,
  `blockchain`, `financial`, `quantum`, `fuzzy_logic`, `genetic_algorithm`,
  `web_programming`, `file_transfer`, `audio_filters`, `scheduling`,
  `networking_flow`, `knapsack`, `linear_programming`, `conversions`, `other`.
- **Practice:** `project_euler` holds solutions to Project Euler problems.

Key root files:

- [`DIRECTORY.md`](DIRECTORY.md) — the complete generated index of every
  algorithm in the repo; the fastest way to find a specific implementation.
- [`CONTRIBUTING.md`](CONTRIBUTING.md) — the contribution rules (style,
  tests, documentation requirements). Read it before opening a PR.
- `pyproject.toml` — project/tooling configuration; `tests/` — the test suite
  that backs the implementations.

## How to use it

1. Search [`DIRECTORY.md`](DIRECTORY.md) for the algorithm you need, or browse
   the matching topic folder.
2. Read the implementation top to bottom — docstrings explain the approach,
   and the `if __name__ == "__main__":` block usually demos it.
3. Run the file directly with Python to see it work, and check `tests/` for
   the corresponding test cases.

## About this standalone edition

This repository is a standalone edition of
[TheAlgorithms/Python](https://github.com/TheAlgorithms/Python), converted
from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to TheAlgorithms and
the Python contributors; licence MIT (see `LICENSE.md`).
