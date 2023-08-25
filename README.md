# SpecCurveTilt : Spectral Curvature and tilt Removal method
Welcome to the GitHub repository for the Spectral Curvature and Tilt Correction Method, designed for calibration lines in high-resolution spectra. Initially developed for Fabry-Perot calibration lines, this technique is also applicable to Th-Ar lines. The code is optimized for high to medium Signal-to-Noise Ratio (SNR) lines and is tailored to accommodate the uniform line density characteristics of Fabry-Perot (FP) and Laser Frequency Comb (LFC) lines.

# Limitations
The current version of the code is adept at addressing curvature and tilt corrections for high SNR lines but is limited in its ability to handle low SNR/faint lines (SNR < 6) and blended lines within Th-Ar spectra. We have plans to address these limitations in future updates.

# Code Details
For a comprehensive understanding of the code and its functionality, please refer to our publication: [Tanya et al. 2021](https://opg.optica.org/ao/abstract.cfm?URI=ao-60-31-9906).

# Data and Testing
We have rigorously tested the code using Fabry-Perot calibration data from the High-Efficiency Spectrograph (HESP) and Th-Ar calibration data from the MIKE and XShooter instruments. As a post-processing technique, it is recommended to utilize bias-subtracted and pre-processed FITS files as inputs for optimal results.

# Disclaimer
Please be aware that the code is currently in its developmental phase. We are working on enhancements and refinements to ensure its effectiveness across various scenarios.

# Citing
If you decide to incorporate this method into your research, we kindly request you to cite our work: [Tanya et al. 2021](https://opg.optica.org/ao/abstract.cfm?URI=ao-60-31-9906)
Your citations contribute to the recognition and further development of this tool.

Thank you for your interest in our Spectral Curvature and Tilt Correction Method. 
We encourage collaboration and feedback from the community to collectively enhance its capabilities.

# Requirements
The code has been developed in Python 3.7.1.
The tracing of apertures has been done using CERES pipeline available on github.

The following python packages are required:
1. python-numpy
2. python-scipy
3. python-matplotlib
4. python astropy
5. python-skimage

