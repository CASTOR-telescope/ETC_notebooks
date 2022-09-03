# ETC_notebooks

Example Jupyter notebooks using the
[`castor_etc`](https://github.com/CASTOR-telescope/ETC) Python package.

## Index

1. [Getting started with photometry](./getting_started_photometry.ipynb)
   - Contains simple examples of how to do photometry with point sources, extended
     sources, and galaxies.
2. [Looking at CASTOR's red leak performance](./redleak.ipynb)
   - A brief introduction to red leak and the concept of a _red leak threshold_, followed
     by calculating the red leak fraction in CASTOR's passbands for blackbodies of various
     effective temperatures.
3. [Custom surface brightness profiles from a FITS file](./custom_source.ipynb)
   - Shows how to bypass the package's internal source generation and use your own FITS
     images with `castor_etc`. This feature allows the user to use the majority of the
     ETC's functionality (e.g., background estimation, aperture generation, etc.) with
     their own data.
4. [Batch processing to generate a S/N table](./snr_table.ipynb)
   - Shows how to process many sources automatically. We find the integration time
     required to achieve some signal-to-noise (S/N) ratio in each of the telescope's
     passbands given sources at various magnitudes.
5. [Customizing a Telescope object to include additional passbands/filters](./passbands_with_filters.ipynb)
   - Demonstrates how to adapt a FORECASTOR Telescope object to include additional 
   transmission curves. As a relevant example, we include new passbands corresponding
   to the UV and u bands with the inclusion of either a longpass or bandpass filter,
   and compute updated S/N tables accordingly.
6. [Getting started with UVMOS spectroscopy](./getting_started_uvmosSpectroscopy.ipynb)
   - Illustrates the use of the UVMOS ETC for making S/N calculations for a given
   input spectrum.
   
