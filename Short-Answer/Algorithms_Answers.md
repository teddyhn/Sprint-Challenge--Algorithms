#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
while loop = O(n)
calculation a = a + n * n constant = O(1)

ans = O(n) * O(1) = O(n)

b)
for loop = O(n)
n is evaluated again in while loop = O(n)

ans = O(n) * O(n) = O(n^2)

c)
function is not dependent on input n so constant = O(1)

ans = O(1)

## Exercise II

1. go to floor n/2 and drop an egg
2. if egg is broken go to floor between floor 0 and floor n/2
3. else if egg is unbroken go to floor between n/2 and n
4. repeat steps 2/3 with the current floor being the "lower bound" if egg is unbroken and the previously visited floor being the "upper bound" (and vice versa if the egg broke) until f is determined

this problem mimics binary search and will have a runtime complexity similar if not identical to it: O(log n)


