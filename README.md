# andreev_spectra

Numerical code accompanying the paper 'Zeeman and spin-orbit effects in the Andreev spectra of nanowire junctions"
by Bernard van Heck, Jukka Vayrynen and Leonid Glazman (Yale university).

This repository contains two files:

1) andreev_spectrum_wire_model.py, containing the code used to numerically find the Andreev bound state energies and wave functions.
2) abs_numerics_and_figures.ipynb, a Jupyter notebook which can be used to reproduce the numerical figures presented in the paper.

The numerical code essentially consists of a root finding function tailored to the determinant equation (25) derived in the paper.
