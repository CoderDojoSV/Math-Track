# Math Track

Welcome! We are going to use code to solve some math problems. You can use any programming language you prefer.

##The Entry Problem

`Print out a list of numbers from 1 to 100 each on a new line. However, if the number is divisible by 4, print your age. If the number is divisible by 7, print your ZIP code. If the number is divisible by both 4 and 7, skip to the next number (don't print anything).`

This type of problem is called a Fizz Buzz test and is common during professional interviews. If you solved it, congratualations! You know how to use conditionals and loops to solve problems, so let's see what else we can do!

###Approaching it as a Venn Diagram
![venn d](http://uvalaw.typepad.com/.a/6a00d8349d72fd69e201676818db67970b-pi)

  There are two different situations to check for:

1. If the number is divisible by 4 - let's call this A
2. If the number is divisible by 7 - let's call this B

  But sometimes we want to skip the line and sometimes we just want to print the number:

3. If both A and B - this is the overlapped part of the Venn Diagram
4. If neither A nor B - this is everything outside the circles in the Venn Diagram

###Many ways to solve the problem

There were two very popular ways to solve it. 

1. Using a combination of: if, else if, else if, else
2. Using 3 nested if/elses (nested means one inside the other)

Which way did you use?


###Writing Pseudo Code

Since there are a variety of programming languages being used, we will using pseudo code to solve how to structure your code. Pseudo means fake - it isn't really a programming language. You still have to turn it into actual code that your computer will understand!

This is a great way to think out how to structure your code before you actually type it out. It's a combination of code logic and actual words. Here is an example:

```
for loop 1 to 100 {
  if A and B {
     skip
  }
  else if A {
     print my age
  }
  else if B {
     print my ZIP code
  }
  else {
     print the number
  }
}
```

###Your Turn!
You are going to solve it again the other way. So if you submitted a solution that used 1 above, use 2 this time. And vice versa. 

Now:
1. Write pseudo code to think through how to structure it
2. Convert it to actual code

##Project Euler Problems

[Project Euler](https://projecteuler.net/) is a website that has challenging math problems that require code to solve them. There are hundreds of problems that quickly become extremely difficult, but some are very similar to our FizzBuzz entry problem.

###Problem 1

[Link to Project Euler problem 1](https://projecteuler.net/problem=1)

`If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000.`

Think about how to structure this solution. I recommend writing pseudo code first and showing it to a mentor before writing any code.

Hint: it's easiest to keep a running total of the sum as you go.

Once you finish, try solving [problem 5](https://projecteuler.net/problem=5) on your own before we keep going as a group.

###Problem 6

See [Project Euler problem 6](https://projecteuler.net/problem=6).

`Find the difference between the sum of the squares of the first one hundred natural numbers and the square of the sum. Click the link above for an example.`

Again, think about it first and write pseudo code. Show a mentor before going on to type out the code on your computer. 

Hint: Use two different for loops and keep a running total for each as you go.

##The Next Step Up In Difficulty

There are plenty of Project Euler problems that require concepts like arrays and recursion to realistically solve them. Here are two more hard problems that don't require more advanced CS concepts that you might like to try:

See [Project Euler problem 12](https://projecteuler.net/problem=12).

See [Project Euler problem 14](https://projecteuler.net/problem=14).

##Do You Like These Kinds of Challenges?

Project Euler has hundreds of more problems, but they get really hard - some require more advanced computer science techniques to solve, where a simple approach might have to run for years before providing an answer! There are two other sites I recommend you try instead. 

[USA Computing Olympiad](http://www.usaco.org/) runs programming competitions for middle and high schoolers. They have extensive training resources that provide fun challenges. 

[TopCoder](https://www.topcoder.com) is another website with interesting challenges. I recommend using the [TopCoder Arena Practice Problems](https://arena.topcoder.com/#/u/practiceProblemList) and filtering for problems with an Easy Difficulty and worth 250 points.

[HackerRank](https://www.hackerrank.com/) is another excellent one to check out.
