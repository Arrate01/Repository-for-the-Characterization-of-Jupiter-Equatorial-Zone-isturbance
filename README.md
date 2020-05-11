# Repository-for-the-Characterization-of-Jupiter-Equatorial-Zone-isturbance
Antuñano et al. (2020) used ground-based mid-infrared (8-20 µm) data acquired by VISIR instrument mounted on the VLT in Chile, COMICS instrument mounted on the Subaru telescope on Maunakea (Hawai'i) and MIRSI instrument mounted on the IRTF (Maunakea) between 2005 and 2008 to characterize the variability of tropospheric temperature and aerosol opacity during the 2006-2007 Equatorial Zone disturbance. 

This repository contains all the cylindrical maps (cmap.fits) and the corresponding emission angle files (mu.fits) used in Antuñano et al. (2020) to compute (i) the zonal-mean brightness temperatures as a function of latitude and date (Figure 4), and (ii) spectral image cubes to derive the vertical profile of temperature and aerosols (Figures 5 and 6). The data is organized by wavelength.

**Important information:**
Due to the maximum chopping amplitude of 25" of the VLT and the small field of view of the VISIR instrument, the chopping-nodding technique used to remove the sky emission from the VISIR data leads to a region of Jupiter being artificially obscured. This is due to part of Jupiter's thermal emission being subtracted together with the sky emission. Please note that these obscured regions have been corrected in the archived VISIR cylindrical maps by adding back the region of the planet that was previously subtracted. Any uncorrected or spurious pixels added by this technique (e.g. artificially brightening and/or obscuring of some pixels) needs to be omitted when using these data.




