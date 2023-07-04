F. Cesarone, A. Scozzari and F. Tardella,  	26-Jun-2008 	 	 
 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
                        EuroStoxx50                         
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
 
returns over time = 	264 	weeks from 	10-Mar-2003 	to 	24-Mar-2008 	 
 
number of stocks = 	48 	 
 
data FOLDER: 
list48.txt (list of stocks; 48X1) 
Ret48_time.txt (returns of each stock over time; 264X48) 
price48_time.txt (prices of each stock over time; 265X48) 
MRet48.txt (expected returns mar2003-mar2007; 48X1) 
Cov48.txt (covariance matrix mar2003-mar2007; 48X48) 
time.txt (dates of returns; 264X1) 
matlab_time.txt (dates expressed in MATLAB serial date number format; 264X1) 
 
 
solutions FOLDER: 
Xi48K5_SolVal.txt (column 1: return; columns 2-6: indices i of optimal solution; columns 7-11: optimal values Xi) 
Xi48K10_SolVal.txt (column 1: return; columns 2-11: indices i of optimal solution; columns 12-21: optimal values Xi) 
RetRisk48_SolVal.txt (column 1: return; columns 2-10: risk values when K=2,3,...,10; columns 11: Unconstrained Markowitz risk) 
 
Note: Missing values in all columns > 1 correspond to infeasible solution for a given return in column 1 
 
 
