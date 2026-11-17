[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17348274.svg)](http://doi.org/10.5281/zenodo.17348274)
# Water Balance Data Fusion Extensions
* generatePandEvariance folder contains the following tools:
  * `MaternEvapV.ipynb`: to generate the evaporation variance timeseries using grid-scale standard deviations and correlation matrix derived using Matérn kernel implemented within a stochastic variational Gaussian Process
  * `MaternPrecipV.ipynb`: to generate the precipitation variance timeseries using grid-scale standard deviations and correlation matrix derived using Matérn correlation function
* `WaterBalanceDataFusion` folder contains the water  balance data fusion model extended to:
  * account for surface water imports from irrigation canals  
  * use ensemble of precipitation and evaporation data sets  
  * quantify posterior cross-correlations between water balance variables using the `MessagesFromMarginals.ipynb` tool in the WaterBalanceMarginalandJointMessages folder   
* `Grid-scaleKalmanUpdate` folder contains tools to perform kalman smoothing described in section 4.2 of the paper. 

![C#](https://img.shields.io/badge/C%23-239120?logo=dotnet&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-8-512BD4?logo=dotnet&logoColor=white) ![Infer.NET](https://img.shields.io/badge/Infer.NET-0.4-5C2D91) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white) ![GDAL](https://img.shields.io/badge/GDAL-5CAE58?logo=osgeo&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![GPyTorch](https://img.shields.io/badge/GPyTorch-6A1B9A) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
