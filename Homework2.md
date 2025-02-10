# Homework 1

1.	Plot the normal distribution fit (Gaussian) and histograms of `data1.dat`, `data2.dat` and `data3.dat`. Which of the datasets are normal distributed?
2.	Determine in a rigorous manner whether `data1` and `data2` are drawn from a normal distribution with some unknown mean and unit variance using a Chi-Square test. Also determine if `data3` is drawn from a normal distribution with some unknown mean and a standard deviation of 4 using the Chi-Square test. Make your conclusions at a stated confidence level.
3.	For InSAR students: In your data identify two particularly noisy displacement time series (no tropospheric correction), one without and the other with a displacement signal.  Obtain a third time series by removing the trend from the time series with a signal.  Determine whether the three time series (the third is a residual) are drawn from a normal distribution using a Chi-Squared test.  Vary the length of the time series. Are particularly noisy periods still normal distributed?

For 3., follow two approaches. First, get a time-series for a site of your choice from https://insarmaps.miami.edu using the ‘Download as TXT’ button.  Write code to remove a trend given by a first or second order polynomial or by an exponential function.  Second, use the MintPy function `timeseries2velocity.py` for this which supports a multitude of temporal deformation models. Quantify the uncertainties using the three implemented methods (`--uq residue`, `--uq covariance`,`--uq bootstrap`). Hint: Start with the second part and do the first after the linear regression homework).

For Giacomo: For the area of the June 2022 Chiles earthquake, estimate the co-seismic displacement using two approaches (i) linear velocity between two dates, (ii) assuming a step function allowing for both first and second order polynomial for the pre- and post-earthquake periods. Present results in a Jupiter Notebook or Powerpoint.  

Non-InSAR students will get a similar homework later in the class.
