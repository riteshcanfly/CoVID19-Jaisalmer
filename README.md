# CoVID19-Jaisalmer
This is the data analysis software for Jaisalmer camp 

This is the data from Jaisalmer centre. 
There are two notebooks (R and Python) both HTML files are also there.
The Rfile take use the earlyR package for getiing R0 value with mu = 7.5 and sigma = 3.5
This produces a maximum likelihood estimation of R0. The R0 value obtained is 0.98 from here.

The Python file introduces SEIR model with parameter estimation
The obtained values are:
* Beta = 8.55686505159+- 
* Gamma = 2.95899586883 
* Delta = 0.280502068839

R0 = Beta/Gamma = 2.8918

The error on the estimates are [ 8.20475418,  0.50799232,  0.29730275] 

This is again very high as expected from low number of data points.
