F. Cesarone, A. Scozzari and F. Tardella,  	26-Jun-2008 	 	 
 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
                        SP_500                         
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
 
returns over time = 	264 	weeks from 	10-Mar-2003 	to 	24-Mar-2008 	 
 
number of stocks = 	476 	 
 
data FOLDER: 
list476.txt (list of stocks; 476X1) 
Ret476_time.txt (returns of each stock over time; 264X476) 
price476_time.txt (prices of each stock over time; 265X476) 
MRet476.txt (expected returns mar2003-mar2007; 476X1) 
Cov476.txt (covariance matrix mar2003-mar2007; 476X476) 
time.txt (dates of returns; 264X1) 
matlab_time.txt (dates expressed in MATLAB serial date number format; 264X1) 
 
 
solutions FOLDER: 
Xi476K5_SolVal.txt (column 1: return; columns 2-6: indices i of optimal solution; columns 7-11: optimal values Xi) 
Xi476K10_SolVal.txt (column 1: return; columns 2-11: indices i of optimal solution; columns 12-21: optimal values Xi) 
RetRisk476_SolVal.txt (column 1: return; columns 2-10: risk values when K=2,3,...,10; columns 11: Unconstrained Markowitz risk) 
 
Note: Missing values in all columns > 1 correspond to infeasible solution for a given return in column 1 
 
 
