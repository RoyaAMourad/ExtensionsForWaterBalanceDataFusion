[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17348192.svg)](http://doi.org/10.5281/zenodo.17348192)
# Water Balance Data Fusion Extensions
* generatePandEvariance folder contains the following tools:
  * `MaternEvapV.ipynb`: to generate the evaporation variance timeseries using grid-scale standard deviations and correlation matrix derived using Matérn kernel implemented within a stochastic variational Gaussian Process
  * `MaternPrecipV.ipynb`: to generate the precipitation variance timeseries using grid-scale standard deviations and correlation matrix derived using Matérn correlation function
* `WaterBalanceDataFusion` folder contains the water  balance data fusion model extended to:
  * account for surface water imports from irrigation canals  
  * use ensemble of precipitation and evaporation data sets  
  * quantify posterior cross-correlations between water balance variables using the `MessagesFromMarginals.ipynb` tool in the WaterBalanceMarginalandJointMessages folder   
* `Grid-scaleKalmanUpdate` folder contains tools to perform kalman smoothing described in section 4.2 of the paper. 
