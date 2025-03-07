# Detecting AGB change using Landsat 9 and Planet imagery in Kwahu South, Ghana

## Background

In this project, AGB density was modeled by using Landsat 9, Planet and GEDI L4A data. The analysis was performed for Kwahu South area. ArcGIS Pro was used to perform the analysis.

## Data summary

-   Landsat 9 imagery

-   Planet imagery

-   GEDI L4A data

## Approaches

-   Use "Mosaics to Raster" to combine 2 Landsat images

-   Use "Project to new Raster" to repoject and resample Planet's image.

-   Calculate spectral indices from Raster Function tool.

-   Use "Train Random Tree Regression" tool to develop a model using calculated spectral indices as explanatory variables

-   Predict the AGB density using the models in previous steps

## Contact

Email
