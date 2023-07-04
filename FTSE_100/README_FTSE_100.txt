F. Cesarone, A. Scozzari and F. Tardella,  	26-Jun-2008 	 	 
 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
                        FTSE_100                         
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
 
returns over time = 	264 	weeks from 	10-Mar-2003 	to 	24-Mar-2008 	 
 
number of stocks = 	79 	 
 
data FOLDER: 
list79.txt (list of stocks; 79X1) 
Ret79_time.txt (returns of each stock over time; 264X79) 
price79_time.txt (prices of each stock over time; 265X79) 
MRet79.txt (expected returns mar2003-mar2007; 79X1) 
Cov79.txt (covariance matrix mar2003-mar2007; 79X79) 
time.txt (dates of returns; 264X1) 
matlab_time.txt (dates expressed in MATLAB serial date number format; 264X1) 
 
 
solutions FOLDER: 
Xi79K5_SolVal.txt (column 1: return; columns 2-6: indices i of optimal solution; columns 7-11: optimal values Xi) 
Xi79K10_SolVal.txt (column 1: return; columns 2-11: indices i of optimal solution; columns 12-21: optimal values Xi) 
RetRisk79_SolVal.txt (column 1: return; columns 2-10: risk values when K=2,3,...,10; columns 11: Unconstrained Markowitz risk) 
 
Note: Missing values in all columns > 1 correspond to infeasible solution for a given return in column 1 
 
 
