# LEC CH2
## Topic: loop with while
Date: Sept 14,2014
### Lesson goal
> - understand the concept of loop
> - initializer the index
> - control the iteration using the index
> - increase the index

----
### Review
Make a program which get a positive integer and print number from 1 to a given positive integer.

Input

````  
Type a postive integer: 7
````

Output

````
1 2 3 4 5 6 7
````
### What is the loop?
To solve a complex job, we may divide it into several simple and **same(similar)** tasks which we can handle. But we need to repeat such tasks;
It is a quiet boring job. Fortunately, computer can help with the loop.
Here the loop means computer repeats the block of codes until it completes our job.

Unfortunately, computer is not so smart. So we need to teach **how to start and end**. We also need to **divide our job into small and similar tasks** which computer can handle. Atually, after we divide our job, we can figure out how many step we can repeat and when to stop.

To control loop process, we usually use the iteration index varable(s).
For each task, we can assgin an index number. If the number 

Let me summarize the process of loop.

> -  Divide the job into small and similar tasks.
> -  Assigin the index number for each task.
> -  **Initialize the index and implement the loop condition(when to stop).**
> - Varies the index.

Recall previous question.

````
A given n, print numbers from 1 to n.
````

Here we have a problem. Since we do not know a number n, we cannot print a sequence of numbers from 1 to n immediately. So let us divide the job into several task. I believe print a number is a smallest  task.

#### STEP1 and STEP 2
First, we print 1. Let it as task 1(**index=1**).<br>
Second, we print 2. Let it as task 2(**index=2**).<br>

..

..

In general, when we print a number *i*, we can put  **index=i**. 

```
TASK i: print i.
```

Of course, *i* varies between 1 and n to print number.
So we have n different tasks indexed by i where i moves from 1 to n.
#### STEP 3
Use i as an iteration index variable.

```
Initializer: i=1
```

```
condition for the loop: i<=n
```
#### STEP 4
```
increase: i=i+1 (increase i by 1)
```
### Coding

Now let us make a code using while statement

#### while

```
 initialize
 while( condition for the loop)
{
  each task
  increase   
}
 next part
```

Computer repeats *each task* during condition for the loop is true.
When condition for the loop is false, computer will stop the loop and move to next part. *increase* part may change the condition, so the loop may stop eventually.












