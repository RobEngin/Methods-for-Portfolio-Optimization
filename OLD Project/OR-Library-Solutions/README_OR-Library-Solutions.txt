F. Cesarone, A. Scozzari and F. Tardella,  	26-Jun-2008 	 	 
 
OR-Library-Solutions FOLDER: 
 
The format of the files in this folder is the following: 
 
Xi??K5_SolVal.txt (column 1: return; columns 2-6: indices i of optimal solution; columns 7-11: optimal values Xi) 
Xi??K10_SolVal.txt (column 1: return; columns 2-11: indices i of optimal solution; columns 12-21: optimal values Xi) 
RetRisk??_SolVal.txt (column 1: return; columns 2-10: risk values when K=2,3,...,10; column 11: Unconstrained Markowitz risk) 
 
 
Note: Missing values in all columns > 1 correspond to infeasible solution for a given return in column 1.
      For ??= 31, 85, 89, 98, 225, the solutions were calculated on the test problems port1.txt, port2, ..., port5.txt, respectively.
      For ??= 457, 1318, 2151, the solutions were calculated on the test problems indtrack6.txt, ..., indtrack8.txt, respectively.
      For the latter test problems where only the time series of the stock values were available, 
      we have constructed the return vectors and the covariance matrices in a standard manner.
      Such return vectors and covariance matrices are available upon request.
 
 
