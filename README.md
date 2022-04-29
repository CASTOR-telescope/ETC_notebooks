# ETC_notebooks

Example Jupyter notebooks using the
[`castor_etc`](https://github.com/CASTOR-telescope/ETC) Python package.

## Index

1. [Getting started with photometry](./getting_started_photometry.ipynb)
   - Contains simple examples of how to do photometry with point sources, extended
     sources, and galaxies.
2. [Custom surface brightness profiles from a FITS file](./custom_source.ipynb)
   - Shows how to bypass the package's internal source generation and use your own FITS
     images with `castor_etc`. This feature allows the user to use the majority of the
     ETC's functionality (e.g., background estimation, aperture generation, etc.) with
     their own data.
3. [Batch processing to generate a S/N table](TODO: make link)
   - Shows how to process many sources automatically. We find the integration time
     required to achieve some signal-to-noise (S/N) ratio in each of the telescope's
     passbands given sources at various magnitudes.
