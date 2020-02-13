# Customized-Curve-Fitting
This Python script contains different forms of curve fitting from simple linear fit to log transformation fit to four parameter hill function fit and guidelines for customizing any functional curve fit.

From the sci.py.optimize package curve_fit we can take advantage of customized functional fitting for data. The algorithm for doing so is rather straightforward, simply define a function with parameters you would like to fit and then run the function curve_fit on it. ie. curve_fit(FUNCTIONNAME, xdata, ydata).
