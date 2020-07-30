# Night-time lights data [![DOI](https://zenodo.org/badge/241801111.svg)](https://zenodo.org/badge/latestdoi/241801111)
Modelled VIIRS-DNB like night-time lights datasets (2004 to 2012)

The Defense Meteorological Satellite Program’s Operational Linescan System (DMSP-OLS) night-time lights earth observation data (earlier provided by [NOAA](https://ngdc.noaa.gov/eog/index.html), now by [Payne Institute](https://payneinstitute.mines.edu/eog/)) is at 1km spatial resolution and is available as yearly composites (1992-2013).

The Visible Infrared Imaging Radiometer Suite’s Day/Night Band (VIIRS-DNB) data is made available at 500m and as monthly composites (April 2012 - December 2019; as on February 20, 2020).

Two studies were done ([Sahoo et al., 2019](https://doi.org/10.1080/01431161.2019.1693077) and Sahoo et al., 2020 (in preparation)) to generate annual composites of VIIRS-DNB data and inter-calibrate with DMSP-OLS, to generate time-series VIIRS-DNB-like night-time lights product.

In this repository the modelled VIIRS-DNB like NTL datasets (using multi-layer perceptron and random forest models) for 2004 to 2012 are made available for download by the researchers.

The study was done for the [State of Uttar Pradesh, India](http://geojson.io/#id=github:prasunkgupta/nightlights/blob/master/UP.geojson&map=7/27.188/80.868). The files are georeferenced and in GeoTIFF format. Readers are referred to papers mentioned above for details of the process.
