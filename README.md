# PLDCheops

In this repository, we will try to use pixel-level decorrelation (PLD) method to correct for instrumental systematics in CHEOPS lightcurve, especially the roll angle correlation.

_Acknowledgements_: The algorithm used here is described in various literature, e.g., [Luger et al. 2016](https://www.doi.org/10.3847/0004-6256/152/4/100). The core code used in the present notebook was developed by Néstor Espinoza to extract photometry from TESS TPF files which can be found [here](https://github.com/nespinoza/PLD-TESS), which was then modified by Jayshil A. Patel to extract lightcurves from [TESS/TICA data](https://github.com/Jayshil/tess-tica) and from JWST/NIRCam short-wave photometry (e.g., [HAT-P-14 b transit lightcurves](https://github.com/Jayshil/hat-p-14/blob/main/NRCSW/p4.ipynb) and [WASP-39 b ERS data](https://github.com/Jayshil/jwst-ers/blob/main/NRCSW/p4.ipynb)).