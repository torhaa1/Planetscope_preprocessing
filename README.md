## Preprocessing of Planetscope 4-band imagery

This repository contains scripts for preprocessing and basic analysis of Planetscope imagery.
Code is based on notebooks from [Planetlabs](https://github.com/planetlabs/notebooks).


## Available notebooks

### Preprocessing
* [PS_preprocess_reflectance_images](https://github.com/t-haakens/Planet_processing/blob/main/PS_preprocess_reflectance_images.ipynb)

Preprocess multiple images that does not need mosaicing.              
Convert Radiance to Reflectance. Deliver images scaled/unscaled, with/without clipping to AOI (area of interest).          

* [PS_preprocess_reflectance_mosaic](https://github.com/t-haakens/Planet_processing/blob/main/PS_preprocess_reflectance_mosaic.ipynb)

For large AOI's that require several scenes/images (mosaic) to cover the AOI.                  
Convert Radiance to Reflectance. Deliver images or the mosaic scaled/unscaled, with/without clipping to AOI.

<br>

### Analysis

* [PS_analysis_veg_indices](https://github.com/t-haakens/Planet_processing/blob/main/PS_analysis_veg_indices.ipynb)

Takes reflectance images as input, calculate, visualize and export vegetation indices from PS 4-band imagery.   
**Vegetation indices**: NDVI, EVI, SAVI, MSAVI2, ARVI, IPVI, DVI, RVI              

* [PS_analysis_segment_threshold](https://github.com/t-haakens/Planet_processing/blob/main/PS_analysis_segment_threshold.ipynb)

Takes vegetation indices as input, apply thresholding to segment image, smoothen with majority filter and export mask.  

<br>

Flowchart illustrating the process going from radiance images to a reflectance mosaic clipped to an AOI.  

<img src="https://github.com/t-haakens/Planet_processing/blob/main/PS_preprocess_flowchart.png" width="700">

> **Note**: If GitHub isn't rendering the images, consider downloading them for local viewing:
> [Download Flowchart](https://github.com/t-haakens/Planetscope_preprocessing/raw/main/PS_preprocess_flowchart.png)
