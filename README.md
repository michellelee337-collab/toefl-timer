# TOEFL Timer

A single-page, no-build practice timer for the redesigned January 2026 TOEFL iBT.

Open `index.html` in any browser, or serve the folder as a static site (it also works as-is with GitHub Pages).

## What it does

- **Full practice test**: all four sections back to back (1 hr 23 min to 1 hr 29 min total). Reading and Listening run as single adaptive clocks; Speaking and Writing step through every task in sequence.
- **Practice by section**: run one section's full clock, or drill a single task type (e.g. Take an Interview, Build a Sentence) with editable per-item timing.
- Manual-start response countdowns for Speaking, so there's time to read each question before the clock runs.
- A single synthesized beep to signal "start speaking," no other sound. A non-audio safeguard (visual flash plus vibration where supported) marks when a response's time is up.
- Progress is saved to the browser's local storage, so closing the tab mid-test doesn't lose your spot.

## Source

Section lengths, item counts, and task types follow the [ETS TOEFL iBT 2026 Test Blueprint](https://www.eu.ets.org/pdfs/toefl/toefl-ibt-test-specifications-2026.pdf). Per-item drill pacing is an editable practice estimate, not an ETS-published figure.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No build step, no dependencies beyond a Google Fonts stylesheet.
