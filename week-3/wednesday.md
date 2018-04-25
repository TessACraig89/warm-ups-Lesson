# Whiteboard Wednesdays! 

This week we will look in depth at one problem. It is a very exciting problem, involving the Fibonacci Sequence, a magical sequence of numbers that is found everywhere in nature, and it is super beautiful.

`0, 1, 1, 2, 3, 5, 8, 13, 21, 34,...` 

![](https://insteading-wpengine.netdna-ssl.com/assets/images/Art/Fibronacci/nautilus%20shell.jpg)

![](http://images.tutorvista.com/cms/images/88/Fibonacci-spiral.jpg)

The sequence builds on itself. It starts by definition with the first two numbers: `0, 1`. Each subsequent number is the sum of the previous two numbers, on into infinity. 

## Instructions: 

With a partner you are going to whiteboard some pseudocode that prints the Fibonacci sequence up to 10 numbers. 
It's OK if it prints this as an Array, or one at a time. Up to you. 

Talk through the problem and verbalize your thought process so you can feed off of eachothers ideas. Brainstorm! This means don't hold back or be afraid to verbalize a dumb idea. There aren't dumb ideas, just stepping stones to the solution!


## Bonus: 

- Modify your pseudocode to print up to N numbers of Fibonacci. In other words, when N is 8, our function should print `0, 1, 1, 2, 3, 5, 8, 13`.

- Write new pseudocode to print every *other* number of the Fibonacci sequence. Watch out! This should not change the sequence itself! Only print every other number in the same sequence. 

## Super Bonus - Recursion 

Warning: this Super Bonus is Super, because it would be challenging even if you had 2x as much time to solve it. But I believe in you! Solve it later if you feel called to do so, or blow our minds and solve it this morning!

Recursion is a method that calls itself. Here's a simple example of a countdown method that uses recursion to count down from any number and than print 'Blastoff!'
```
FUNCTION countdown (n)
  if n == 0
    print 'Blastoff!' 
  else
    print n
    countdown(n - 1)

countdown(5)
```

Take a little time to understand what's happening here, and then think about how our Fibonacci challenge might be solved using recursion! 
