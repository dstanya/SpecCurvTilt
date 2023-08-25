# HRes_tiltRemoval
Method of curvature and tilt correction of calibration lines in high-resolution spectra. This method has been developed for Fabry-Perot calibration lines, 
but it can also be used for Th-Ar lines. The code works well on high to medium SNR lines and has been developed keeping in mind the uniform line density of FP and LFC lines.
The main limitation of the current code is the ability to deal with low SNR/faint lines (SNR<6) and blended lines of Th-Ar spectra.
These limitations will be dealt with in the future.

More details about the code, is given in: [Tanya et al. 2021](https://opg.optica.org/ao/abstract.cfm?URI=ao-60-31-9906).

The code has been tested on FP calibration data from HESP and Th-Ar calibration data from MIKE and XShooter.
Since this is a post processing technique, a bias subtracted and pre-processed fits file should ideally be used as input.

Disclaimer: Code is still under development!

Kindly cite [Tanya et al. 2021](https://opg.optica.org/ao/abstract.cfm?URI=ao-60-31-9906) if you are using this code for your research.

# Requirements
The code has been developed in Python 3.7.1.
The tracing of apertures has been done using CERES pipeline available on github.

The following python packages are required:
1. python-numpy
2. python-scipy
3. python-matplotlib
4. python astropy
5. python-skimage

