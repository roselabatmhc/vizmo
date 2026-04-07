# Vizmo

Visualization software for PMPL problems and results.

## Setup


After cloning this repo:
- Switch to the repo's root directory `cd vizmo`.
- Make the smallest possible clone of PMPL's vizmo branch: `git clone https://github.com/parasollab/open-ppl.git --depth 1 --branch vizmo pmpl`.
- Switch to the PMPL root directory `cd pmpl`.
- Soft-link to your pmpl\_utils copy `ln -s ../../pmpl_utils`.
- Go to `vizmo/src` and build everything with `make`.
