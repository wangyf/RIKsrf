#Code for calculating 1D synthetics
------------------------------------------

The code `RIKseisdwn.f90` combines Green's functions from Axitra with the RIK slip rate functions. The output is full-wavefield velocity seismograms. The source code can be compiled and executed by script `RIKseisdwn.sh`.

Credits:
- Subroutines from Numerical recipes (FFT, spline interpolation).
- Subroutine XAPIIR (IIR filter design and implementation) by Dave Harris (1990).
