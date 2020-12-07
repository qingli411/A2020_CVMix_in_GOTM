# Meteorological data for Gotland Basin

This folder contains the meteorological data for the Gotland Basin test case.
See [here](https://gotm.net/cases/gotland_deep/) for a description of the test case.
This test case is also available at the [GOTM test case repository](https://github.com/gotm-model/cases/tree/master/gotland).
The differences are that:

- The meteorological data is from the [COSMO-REA6 regional reanalysis data for Continental Europe](https://reanalysis.meteo.uni-bonn.de/?COSMO-REA6)
- The surface Stokes drift is from the [CMEMS WAM hindcast of the Beltic Sea](https://resources.marine.copernicus.eu/?option=com_csw&view=details&product_id=BALTICSEA_ANALYSIS_FORECAST_WAV_003_010)

The meteorological data and Stokes drift are preprocessed using `preprocess_Gotland_meteo.ipynb` and `preprocess_Gotland_Stokes_drift.ipynb`.
