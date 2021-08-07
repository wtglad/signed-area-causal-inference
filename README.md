# signed-area-causal-inference
This repository contains code demonstrating the methods outlined in Path Signature Area-Based Causal Discovery in Coupled Time Series presented at Causal Analysis Workshop 2021.

## Usage
Details of the algorithm are available in the paper (link forthcoming), but approximate steps in the code are given by 
1. Get multivariate time series data
2. Scale each series to have mean 0 and range 1
3. Perform shuffled signed area deviation (SSAD) test to analyze significance of signed area sequence. Higher magnitude values will suggest the existence of a causal link between two variables, but will not indicate the direction of the causal relationship. The absolute value of this SSAD represents a confidence that a causal link exists.
4. To determine the causal direction, perform the time-shifted signed area variance ratio test.

## Contact
Feel free to open an issue with any questions or comments. 

