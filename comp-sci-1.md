Pushing and reversing vs shifting: when you shift a number to the front of an array it has to go and move every single number down a slot in order to make that shift happen. Which means the computer has to perform a step for every number in the array. When pushing, the computer only has to perform one step by making a new slot at the end of the array. 

### Speed slide
"n" stands for workload, or the amount of items in an array. Time is in milliseconds. 

Push has a linear time complexity, shift has a quadratic time complexity. 


### Runtime complexity.

Workload normally means the length of the array or list that we're working with, but there are other types of workload. **What are those other types?**

**Sending Data** Plane rate would be constant, cable modem linear

O(n) would be linear time, because the time increases at the same rate as the input
O(n<sup>2</sup>) is quadratic time


**Worst case** We don't have to know what % of someLargeList is even because the calculation of that list is linear, **it's always based on the input, or the length of someLargeList**. So to tell the time complexity we don't need to know the % of even numbers. 

O(1) Constant
O(log n) Logarithmic time complexity
O(n) linear
O(n log n)
O(n<sup>2</sup>) quadratic 

Time complexity is concerned with the rate of increase, not necessarily the time involved for any given example. 

Exponential time is an even steeper curve than quadratic time.

Factorial time is insanely slow. Absolute worst case scenario, rarely going to run in to this. 


**data structures**

You would use a Queue to stop anyone else (including other devs) from messing with your data, since you can design the methods to interact with the array that's under the hood. 


Queues and Stacks are not inherent to any coding language, they are concepts that we would have to implement manually into a JS project. Typically through a class with custom methods. 

Trees are logarithmic


Make a linked list after the lab for extra credit. 
