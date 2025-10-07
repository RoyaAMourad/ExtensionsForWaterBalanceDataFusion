[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17216050.svg)](http://doi.org/10.5281/zenodo.17216050)
# Water Balance Data Fusion Extensions
* generateCorrelationMatrices folder contains the following tools:
  * `MaternEvapR.ipynb`: to generate the evaporation correlation matrix using a Matérn kernel implemented within a stochastic variational Gaussian Process
  * `MaternPrecipR.ipynb`: to generate the precipitation correlation matrix using Matérn correlation function
* `WaterBalanceDataFusion` folder contains the water  balance data fusion model extended to:
  * account for surface water imports from irrigation canals  
  * use ensemble of precipitation and evaporation data sets  
  * quantify posterior cross-correlations between water balance variables using the `MessagesFromMarginals.ipynb` tool in the WaterBalanceMarginalandJointMessages folder   
