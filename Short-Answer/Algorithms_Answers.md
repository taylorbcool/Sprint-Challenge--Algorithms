#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Because a is iterating over n * n every loop, the running time will be O(n).


b) Since j is doubled with each loop until it is larger than n, the runtime will be O(log n)


c) I believe this would be O(n) because the function is called recursively n - 1 times.

## Exercise II

I would take the midpoint between 0 and n, we'll call it x, and drop one egg from that floor. If it breaks I will take the midpoint between 0 and x, and drop an egg from there. If it doesn't break I'll use the same strategy but between x and n. I would continue with this strategy until I find floor f. By doing this repeatedly I will find floor f using the fewest number of eggs.