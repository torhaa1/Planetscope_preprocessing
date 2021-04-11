# Planet processing

This repository contains scripts for processing of Planetscope imagery.
Code is based on notebooks from Planetlabs, available here: https://github.com/planetlabs/notebooks

## Available notebooks

### Preprocessing
* [PS_preprocess_reflectance_images](https://github.com/t-haakens/Planet_processing/blob/main/PS_preprocess_reflectance_images.ipynb)

Convert Radiance to Reflectance. Deliver images scaled/unscaled, with/without clipping to AOI (area of interest).

* [PS_preprocess_reflectance_mosaic](https://github.com/t-haakens/Planet_processing/blob/main/PS_preprocess_reflectance_mosaic.ipynb)

Convert Radiance to Reflectance. Deliver images or the mosaic scaled/unscaled, with/without clipping to AOI.




### Analysis

* [PS_analysis_veg_indices](https://github.com/t-haakens/Planet_processing/blob/main/PS_analysis_veg_indices.ipynb)

Takes reflectance images as input, calculates vegetation indices from PS 4-band imagery and export results.   
 NDVI, EVI, SAVI, MSAVI2, ARVI, IPVI, DVI, RVI

* [PS_analysis_segment_threshold](https://github.com/t-haakens/Planet_processing/blob/main/PS_analysis_segment_threshold.ipynb)

Takes suitable vegetation indices as input, segment image with simple thresholding, smoothen with majority filter and export mask.
