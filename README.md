# solspec
## Abstract:
`solspec` is a collection of [python 3.5](https://docs.python.org/3.5/#) routines related to
the [ASTM Solar Spectral Irradiance Air Mass 1.5](http://rredc.nrel.gov/solar/spectra/am1.5/#about) spectrum. The main
objective at this early stage is to be able to calculate the absorbed photocurrent of solar cells exposed to the
ASTM173-03 Global Tilt spectrum for comparison to others.

### jsc
The jsc method is the main function, which can be fed a discrete spectrum of wavelengths (nm) in ascending order and the
 corresponding normalized spectrum values in order to predict the maximum short-circuit current density of solar cell.

