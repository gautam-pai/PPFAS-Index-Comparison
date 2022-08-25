# PPFAS-Index-Comparison
This is a Tableau visualization of how the Parag Parikh Flexi Cap Fund(PPFAS) has performed against various indexes.

In this we can see that with a little bit of tweak in the ratio of investments in combination of various indexes we can achieve the same returns as PPFAS fund.

To compare the data, 
The NAV(Net Asset Value) of PPFAS Fund since its inception in 23-May-2013 is available in https://amc.ppfas.com/schemes/nav-history/

The Nifty50 Index close points is available in https://finance.yahoo.com/quote/%5ENSEI/history?p=%5ENSEI

The Nasdaq100 Index close points is available in https://finance.yahoo.com/quote/%5ENDX/history?p=%5ENDX

The values are then normalized, by divinding with a constant(value of 23-05-2013)

These are stored in different tables, then joined on the basis of date column.


