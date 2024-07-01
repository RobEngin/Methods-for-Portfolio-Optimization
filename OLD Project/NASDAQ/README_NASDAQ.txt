F. Cesarone, A. Scozzari and F. Tardella,  	26-Jun-2008 	 	 
 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
                        NASDAQ                         
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
 
returns over time = 	264 	weeks from 	10-Mar-2003 	to 	24-Mar-2008 	 
 
number of stocks = 	2196 	 
 
data FOLDER: 
list2196.txt (list of stocks; 2196X1) 
Ret2196_time.txt (returns of each stock over time; 264X2196) 
price2196_time.txt (prices of each stock over time; 265X2196) 
MRet2196.txt (expected returns mar2003-mar2007; 2196X1) 
Cov2196.txt (covariance matrix mar2003-mar2007; 2196X2196) 
time.txt (dates of returns; 264X1) 
matlab_time.txt (dates expressed in MATLAB serial date number format; 264X1) 
 
 
solutions FOLDER: 
Xi2196K5_SolVal.txt (column 1: return; columns 2-6: indices i of optimal solution; columns 7-11: optimal values Xi) 
RetRisk2196_SolVal.txt (column 1: return; columns 2-5: risk values when K=2,3,4,5; columns 6: Unconstrained Markowitz risk) 
 
Note: Missing values in all columns > 1 correspond to infeasible solution for a given return in column 1 
 
 
