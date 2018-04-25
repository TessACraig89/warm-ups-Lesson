# Whiteboard Wednesday! 

## Search Algorithms

#### Binary Search!

**Work in pairs or small groups**

Today you are going to work on implementing the Binary Search algorithm. 

For this basic Binary search implementation, our function:

1. takes a **pre-sorted array** of integers, ex [2, 33, 56, 333, 1989, 112223, 579878989]
2. takes an integer we are searching for
3. returns the **index** of the integer, or "Not found", if the integer is not in the array. 

The goal is to go **faster** than looping over the entire array. 

#### How it works

Binary Search is called that because we split the array in half, and keep splitting it until we find our item. 
We want to split the array in half, and check the first number in the second half of the array. If it is lower than our integer, we know our integer is in the second half, and we can discard the first half. If it is higher, we can discard the second half. We keep doing this until we find our integer, or return "Not found."

#### Exercise

1. Implement Binary Search as best you can on a whiteboard
2. At 8:45, check out [these solutions](https://gist.github.com/JonathanSpeek/1f4c7c283c7c3c475ee13d57381765d8) in Python
3. Discuss with your classmates.

Take a break at 10 AM, lesson one begins at 10:07.
