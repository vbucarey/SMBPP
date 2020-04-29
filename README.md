# smbpp
Instances for the single-minded bundle price problem m = number of clients n = number of products d = density of each bundle. d = number of products in each bundle/n

We have two types of instances:

Uniform: Instances with m in {25,50,100,150} clients and n in {25,50,75} products and densities d in {0.1, 0.2, 0.4}. Budgets are created randomly uniform between 1 and 1000. For each value of n, m and we create 10 random instances.

Rich-Poor instances: Instances with m=100, n=25 and d = 0.2. Their considers a set of m1 poor clients with budgets generated between 1 and 500; and m2 rich clients with bounded generated between 1000 and 1500. Instances consists in (m1,m2) in {(25,75),(75,25),(50,50)}.

