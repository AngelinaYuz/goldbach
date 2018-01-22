## Goldbach Conjecture

### Introduction

**What it does**

This program finds all pairs of primes that make up even numbers more than two and up to a certain number. Then it plots how long the program takes to find all of those pairs, something used for optimization as the program is still in progress, and then finally plots each even number and how many pairs of primes it has. 

**The goal**

My goal is for this program to be able to calculate all of the pairs of primes for each even number up to a million, as right now the program is too slow to be able to do so. 

Wikipedia has a chart that I want to replicate:

<img align="left" width="400" src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Goldbach-1000000.png">

What I get is pretty close:


### Development Process (Still in Progress)

I decided to use Jupyter notebook as it's easy to write code and do graphs. 
	
The original pair generator was written and it would print out all of the pairs as part of the program.
Then, in order to make the graph, some minor adjustments were made to the program, like making it so the program can count the number of pairs there are for each even number and the graph was made.

After that, the program was too slow and wasn’t able to reach a million, so I started optimizing the program, which started with turning most of the main program into a function, adding in a part that times how long the program takes to calculate, and finally, makes a time graph.

Now, I am in the process of optimizing the main program. 

**Stay tuned and star my project if you like it!**

