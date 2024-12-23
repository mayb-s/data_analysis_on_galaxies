### Galaxy Data Analysis with Machine Learning

This repository contains Python code for analyzing nearby galaxies using machine learning models, 
specifically K-means clustering and linear regression. 
The data used is sourced from the NASA/IPAC Extragalactic Database (NED) 
and includes galaxy properties such as Right Ascension (RA), Declination (DEC), Type, Velocity, Redshift, and more. 

The analysis aims to validate Hubble's Law and explore the relationship between redshift and radial velocity, 
along with addressing limitations and biases in the data.



#### Overview

Astronomical data can be vast and difficult to analyze manually.
This project leverages machine learning models to automate the analysis process, 
making it easier to interpret complex galaxy data. 
Key insights such as the correlation between redshift and radial velocity are explored, 
along with an examination of biases in the data due to technological limitations.

The project includes:
- **K-means clustering** to group galaxies based on their properties.
- **Linear regression** to explore the relationship between redshift and radial velocity, validating Hubble’s Law and the expanding universe.

#### Prerequisites

To run the code, you'll need the following Python libraries:
- `pandas` - for data manipulation
- `numpy` - for numerical operations
- `matplotlib` - for data visualization
- `scikit-learn` - for implementing K-means clustering

