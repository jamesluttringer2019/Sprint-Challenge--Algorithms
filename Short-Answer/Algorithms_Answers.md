#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because while loop has n**3, but increments by n**2 so n**3/n**2 = n


b) O(nlogn) since outer for loop is O(n), and each time this loop runs, the inner while loop
also runs, but has O(logn) since the counter doubles each iteration.


c) O(n) since each recursion decreases n by 1

## Exercise II

I would approach this using a binary search technique. I would start at the middle floor, drop an egg, if it breaks, move to the middle of the lower half, and so forth.
If it doesn't break, I would find the midpoint of the upper half, and continue in the same fashion.
this would continue until we find the point where the egg breaks at f, but not f-1

This would run in O(logn) time 