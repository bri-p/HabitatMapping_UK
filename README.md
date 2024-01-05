# HabitatMapping_UK

This repository contains python code for processing, analysing and visualising the data presented in \*"Leveraging Remote Sensing for On-Ground Biodiversity Net Gain Assessments"\* by Brianna Pickstone for the Term 1 Assessment UKRI Centre for Doctoral Training in Environmental Intelligence .

**Data Source:** This study uses a combination of data:

1.  Sentinel-2 Data, downloaded from Google Earth Engine (GEE)

2.  UKCEH Land Cover Map 2021 10 m resolution from <https://digimap.edina.ac.uk/>

    **Contact**: [bp424\@exeter.ac.uk](mailto:bp424@exeter.ac.uk){.email}

## **Scripts**

**This repository contains the following scripts:**

*Download_S2.ipynb* This script contains code for downloading the Sentinel-2 Data from the GEE for the required location in 2021 and 2023.
*Preprocessing.ipynb* This script contains the code for preprocessing the Sentinel-2 and UKCEH data, including the calculation of vegetation indices
*Initial_Analysis.ipynb* This script contains the code for using Random Forest to classify land cover
