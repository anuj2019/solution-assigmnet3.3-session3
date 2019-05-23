# solution-assigmnet3.3-session3
1. Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns. 

Ans. Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns.
mymat <- matrix(rep(1:5, 4), ncol = 4)
mymat [,1] [,2] [,3] [,4] [1,] 1 1 1 1 [2,] 2 2 2 2 [3,] 3 3 3 3 [4,] 4 4 4 4 [5,] 5 5 5 5
apply(mymat, 1, sum) [1] 4 8 12 16 20
apply(mymat, 2, sum) [1] 15 15 15 15

