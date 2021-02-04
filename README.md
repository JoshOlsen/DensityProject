# DensityProject
The attach burn probabilities notebook combines Microsofts building footprints shapefile data with LANDFIRE raster burn probability data. To do this the data is first converted into a common format and then combined for the entire Western United States. 

The density dask procedure notebook uses the dask library for parallel computing to join data from Zillow's ZTRAX assessor and transactions database to every wildfire in the Western US. This was done using Kamiak, the Washington State University computing cluster. 

The density project notebook conducts a simple probit regression for the probability that a wildfire reaches a house based on the home's distance to the wildfire's ignition point. 

Each of these are in various stages of completeness, please contact me at josholse@gmail.com for a current version or for any questions. 
