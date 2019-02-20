# complex_hailstone_sequence

The hailstone sequence is one defined by
Xn = X(n-1)/2 if xn-1 is even
      3* Xn-1 + 1 otherwise
Eventually, for natural number values of X1, the hailstone sequence will converge to the cycle Xr = 1; Xr+1 =
4; Xr+2 = 2; Xr+3 = 1;. This is not immediately obvious, but it does happen for all the inputs 1; 1M.
In this question, I generalized hailstone defined by:
Xn = X(n-1)/2 if Xn-1 is even
      aXn-1 + b otherwise
where a and b are integer valued in (0,1,2....,10). For each of these 121 possible combinations of a and b, I found
out whether or not the sequence converges for all X1 values 1,.....,1000. If the sequence does converge for
all these values, I found out how many di¤erent cycles the sequence converges to.
