# Spectra
Reduced spectra of the E-XQR-30 quasar sample. 
For each quasar in the sample, two binary FITS files are released: one with the combined VIS and one with the combined NIR frames, both rebinned to 10 km/s. 
The naming convention is target_arm.fits, where "target: is the target name as reported in Table 1 of D'Odorico et al. 2023, "arm" is the spectral arm (NIR or VIS). The FITS table columns are:  

- WAVE: wavelength in the vacuum-heliocentric system (A); 
- FLUX: flux density with the telluric features removed (erg cm-2 s-1 A-1);
- ERROR: error of the flux density (erg cm-2 s-1 A-1); 
- FLUX_NOCORR: same as flux, but with the telluric features (erg cm-2 s-1 A-1);
- ERROR_NOCORR: error of flux\_nocorr (erg cm-2 s-1 A-1)). 

A third data product is released for each quasar which is the combined VIS + NIR spectrum rebinned to 50 km/s and normalized to the J(AB) magnitude. These tables are created from the telluric corrected spectra and have the following columns:

- x: wavelength in the vacuum-heliocentric system (nm); 
- xmin: minimum wavelength of the pixel (nm);
- xmax: maximum wavelength of the pixel (nm);
- y: flux density with the telluric features removed (erg cm-2 s-1 A-1);
- dy: error of the flux density (erg cm-2 s-1 A-1). 
