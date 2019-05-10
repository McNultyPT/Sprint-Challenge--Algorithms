## Exercise I

a) O(n) because the loop relies on the value of n, which means as n grows the operations will grow with n.

b) O(n^3) because it's n * n * n for the 3 loops.

c) O(n) I think, because it is being called recursively n times before the base case.

## Exercise II

I would take the the number of floors and find the middle floor then throw an egg from that floor to see if it breaks. If it does break then find the middle floor for the lower half of the floors and so on. At which point the egg doesn't break, then I would start incrementing floors up and throwing the egg off until it breaks. Once it breaks I would go back to the floor below. 

I believe this solution would be O(n^2) because I think I would need 2 loops to iterate over the floors.
