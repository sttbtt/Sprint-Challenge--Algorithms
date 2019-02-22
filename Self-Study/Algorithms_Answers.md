Add your answers to the Algorithms exercises here.

## Exercise I

a. O(n)
the code always runs n times for n input

b. O(n^2)
because of the multiple for loops this code increases expontially as n increases

c. O(n)
really there is not a Big O for this code because it doesn't run becuase of a typo, but if that is fixed it would be O(n + 2) which can just be reduced to O(n)

## Exercise II

divide f by 2, drop the egg, if it breaks divide by 2 the lower half of f / 2 and drop another egg, repeat the division until egg doesn't break, if it doesn't break divide the upper half by 2, repeat the division until egg doesn't break, once the break/doesn't break point is found add 1 to the lower half to make sure the egg breaks, or subtract 1 from the upper half to make sure it breaks