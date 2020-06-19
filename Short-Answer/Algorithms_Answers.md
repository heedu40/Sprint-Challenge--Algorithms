#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(1)


b) O(n^2)


c) O(1)

## Exercise II

1. Drop the egg from the middle floor. If the return value is "Egg Broke", move to the current floor minus one and try again until return is "Egg Not Broke"
2. If the return value from the middle floor is "Egg Not Broke", move to the current floor plus one until the return value is "Egg Broke"
3. Once the return value is "Egg Broke" move to the current floor minus one and return.
4. The runtime of the current implementation would be O(log n).