# :volcano: Santorini-FWI

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kmch/Santorini-FWI/HEAD)

`Jupyter` notebooks with the workflow of the *full-waveform inversion* of the seismic data collected in the PROTEUS experiment around the Santorini volcano, *Christiana-Santorini-Kolumbo* volcanic field.

A part of the repository serves as supplementary materials for the PhD thesis *High-resolution imaging beneath Santorini volcano* by Kajetan Chrapkiewicz.

## How to use it
The notebooks present the entire FWI workflow which can be followed to analyse other datasets. The Python code is fully runnable after setting up the required Python packages listed below, all to be found at https://github.com/kmch/.

## Requirements
The main framework is implemented in the <a href="https://github.com/kmch/FullwavePy">`fullwavepy`</a> package. Some parts of it are in the process of being replaced by standalone packages: `arrau`, `plotea`, `iogeo`, `nutshell`, `susgy`, `qcphi` to alleviate the excessive coupling between `fullwavepy` modules. These packages are currently private as being in the development stage.

Packages `IMMERSE` (written in Fortran 90) and `hickspy` that implement features required to invert geophone/land data will be available upon request after a licence agreement.

## References
The PhD thesis, with other references therein, will be available at https://spiral.imperial.ac.uk/ as soon as the Imperial College London processes it.
