---
title: "A long-term reconstruction of a global photosynthesis proxy over 1982–2023"
collection: publications
permalink: /publication/scidata-lscpp
excerpt: ""
date: 2025-03-03'
venue: 'Scientific Data'
paperurl: 'https://www.nature.com/articles/s41597-025-04686-6'
citation: 'Fang, J., Lian, X., Ryu, Y., Jeong, S., Jiang, C., & Gentine, P. (2025). A long-term reconstruction of a global photosynthesis proxy over 1982–2023. Scientific data, 12(1), 372.'
---

[Download paper here](https://www.nature.com/articles/s41597-025-04686-6)
[Download code here](https://github.com/JianingFang/LCSPP_Scientific_Data)

## Data Access
The primary outputs of this study are long-term reconstructed solar-induced fluorescence proxies (LCSPP-AVHRR) from 1982-2022. The following versions of the data are available:

1. **LCSPP-AVHRR (v3.2)**:
   - 1982-2000: [Zenodo Link](https://doi.org/10.5281/zenodo.7916850)
   - 2001-2023: [Zenodo Link](https://doi.org/10.5281/zenodo.11906675)


2. **LCREF-AVHRR**: Long-term continuous reflectance record from AVHRR (1982-2023):
   - [Zenodo Link](https://doi.org/10.5281/zenodo.11905959)
   - Users can compute red/NIR-based vegetation indices such as NDVI, kNDVI, and NIRv from this dataset.

3. **LCSPP-MODIS**:
   - 2001-2023: [Zenodo Link](https://doi.org/10.5281/zenodo.11658088)

4. **LCREF-MODIS**:
   - 2001-2023: [Zenodo Link](https://doi.org/10.5281/zenodo.11657458)

### Data Format
- All datasets are provided at a 0.05° spatial resolution and biweekly temporal resolution in NetCDF format. Each month is split into two files:
  - File "a": Days 1-15
  - File "b": Days 16-end of the month
 
### Usage caveat:
We note that LCSPP is a SIF-informed photosynthesis proxy and should not be treated as SIF measurements. Although LCSPP has demonstrated skill in tracking the dynamics of GPP and PAR absorbed by canopy chlorophyll (APARchl), it is not suitable for estimating fluorescence quantum yield.
