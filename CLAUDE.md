# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

A personal learning repo for working through quantitative economics / econometrics in Python ("QE M in Py"). As of the first commit it contains only reference readings — there is no code, build system, test suite, or dependency manifest yet. Add those (and update this file) as exercises are written.

## Layout

- `Readings/` — source material driving the work:
  - `quantecon-python-intro.pdf` — Sargent & Stachurski, *A First Course in Quantitative Economics with Python* (https://intro.quantecon.org/intro.html)
  - `ITER.pdf` — Hanck et al., *Introduction to Econometrics with R* (https://www.econometrics-with-r.org). Its examples are in R; work here translates them to Python.
  - `source_readings.txt` — links to all sources, including ones without a local PDF: Cunningham's *Causal Inference: The Mixtape* (https://mixtape.scunning.com) and UCLA's Stata Learning Modules (https://stats.oarc.ucla.edu/stata/modules/).

## Notes

- The PDFs are large (~25 MB and ~4.5 MB). Use the `pages` parameter when reading them rather than loading whole files.
- When porting R or Stata examples from the readings, prefer the Python ecosystem the QuantEcon book uses (NumPy, pandas, Matplotlib, SciPy, statsmodels).
