#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The code in this case is O(n) because the while is n, but the equation is 1.


b) The code in this case is O(log n) because the in range will run n times, but the while will run until a condition is met.


c) The code in this case is O(n) because the code scales linearly with how many bunnies there are.

## Exercise II

I believe the best method is to use the binary search. We would start at the middle floor and drop the egg. If the egg breaks, we can rule out all floors above. Then we pick the new middle and drop again. We repeat this process until the egg doesn't break. Once we find the safe floor this way, we can also assume every floor below is also safe.

Because we're going through not every item, the run time is O(log n).
