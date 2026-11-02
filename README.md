# Land-use-informed Regional Impact Risk Classification (RIRC) Analysis Pipeline

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23235356.svg)](https://zenodo.org/records/23235356)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Overview

The **land-use-informed regional impact risk classification (RIRC)** framework is an analytical workflow designed to assess and map spatial impact risks posed by alien invasive species. It couples two distinct components:

1. **Hierarchical Species Distribution Modeling (SDM):** A global climatic model combined with a nested regional model integrating high-resolution land use/land cover (LU/LC) data to refine local habitat suitability.
2. **LU/LC-Based (S)EICAT Impact Assessment:** Spatially explicit impact risk estimates that disentangle potential impacts into distinct ecological (EICAT) and socio-economic (SEICAT) mechanisms, mapped at fine regional scales according to the specific LU/LC types where each mechanism manifests.

While demonstrated using ***Sorghum halepense*** (Johnsongrass) and Switzerland as a regional case study, the script has been fully generalized and can be applied to any species and target study region.

This research was funded by the Swiss National Science Foundation (SNSF):
SNSF Scientific Exchange Grant: ‘Predicting the Potential Spatial Impact of Alien Invasive Plants for Regionally Informed Decision-Making’ (Grant No. IZSEZ0_229771).
Participating institutions: University of Tehran and Agroscope.

If you use this pipeline in your research, please cite the Zenodo archive:

Oveisi, M., & Maggini, R. (2026). Land-use-informed Regional Impact Risk Classification (RIRC) analysis pipeline (Version v1.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.23235356
---

## Repository Structure

* `Script_land_use_informed_RIRC_v1_20261026.R`: The complete analysis pipeline in R.
* `CITATION.cff`: Machine-readable citation metadata for the software.
* `LICENSE`: GNU General Public License v3.0.
