1. You can directly run "Test-Copy3" based on the dataset "ORCL.csv"
   You also don't need to run it again, since run once takes about 2 minutes

2. It's pretty easy for you to change the dataset and run again. But in order to save time first, use "ORCL.csv"
   You can change to your own stock later.

3. Not important: You can change K, L, R whatever you want. I set K = S0 (ATM Option) and R = 0 (easier). 

X. Column "Knock-out" in df  ->  This is a signal
   if signal = 1 : The stock is already knocked out at this day (because prices before hits barrier)

4. Function "Black-Scholes" gives an analytical formula for price and delta ( delta still has problems -> Seem like Solved 4am by Yingchao and me)

5. Function "Monte-Carlo", you know it  ->  St follows GBM  ->  S(t) = S(t-1) * exp{...}  &  boundary condition ( Found new problems, I may solve it tomorrow )

6. Other functions, not important. Ignore.

7. If it's complicated for you to understand the codes immediately, wait for me and write report first! 
   I'll walk you through it in 10 minutes. So, please take time to finish report first, please!

8. VaR and other parts, easy. I may handle it or let Le Zhu do (She may not have anything to do)

9. Bro, I trust your GRE writing! We shall submit the BEST report!

