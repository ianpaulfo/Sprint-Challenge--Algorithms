#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(N)

The running time of this (while loop) with respect to the input size n of each is O(N). 


b) O(n log n)

The running time of this (nested loops) with respect to the input size n of each is O(n log n):
for n=1 it runs 0 times, for n=5 it runs 15, for n=20, it runs 100. There is a curve but it's not exponential, so my guess would be it's O(n log n).


c) O(N)

The running time of this  (if-then-else statement) with respect to the input size n of each is O(N) because either sequence 1 will execute, or sequence 2 will execute. Therefore, the worst-case time is the slowest of the two possibilities: max(time(sequence 1), time(sequence 2)). In this case, the sequence 1 is O(1) and sequence 2 is O(N), the worst-case time for this whole if-then-else statement would be O(N).

## Exercise II

Drop an egg midway up

if it doesn't break, go halfway between the midpoint you just dropped form and the top of the building. Repeat process from this new midpoint.

if it breaks, go halfway between the point you just dropped from and the bottom of the building. repeat this process form this new endpoint.

this is like binary search, and has a time complexity of O(log n).

