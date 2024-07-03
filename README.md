# C While/do-while Loops
to understand C While/do-while Loops


C Loops

In computer programming, loops are used to repeat a block of code. Loops in Programming come into use when we need to repeatedly a block of statements.

For example, let's say we want to show a message 100 times. Then instead of writing the print statement 100 times, we can use a loop.

That was just a simple example; we can achieve much more efficiency and sophistication in our programs by making effective use of loops.

In programming, a loop is a sequence of instructions that is repeated until a certain condition is reached.

 

Types of Loops

There are 3 types of loops in C:

1) for loop

2) while loop

3) do...while loop

while Loop

while Loop is an Entry Controlled Loop or we can say repetition control structure.
The while loop is used in situations where we do not know the exact number of iterations of loop beforehand.
The loop execution is terminated on the basic of the test condition.
Syntax :

while(condition)

{

  // statements inside the body of the loop

}

 How while loop works?

A while loop evaluates the condition.
If the condition evaluates to true, the code inside the while loop is executed.
The condition is evaluated again.
This process continues until the condition is false.
When the condition evaluates to false, the loop terminates.

 do...while Loop


 Like while loop the do-while loop execution is also terminated on the basis of test condition.
The do-while loop is exit-controlled loop.
In do-while loop the loop body will execute at least once irrespective of test condition.
 

Syntax :

 

do {

// body of loop;

}

while (condition);



 How do-while loop works?

The body of the loop is executed at first. Then the condition is evaluated.
If the condition evaluates to true, the body of the loop inside the do statement is executed again.
The condition is evaluated once again.
If the condition evaluates to true, the body of the loop inside the do statement is executed again.
This process continues until the condition evaluates to false. Then the loop terminates.


Nested do-while Loop

A do-while loop within another do-while loop is called Nested do-while loop.

 

Syntax :

do {

  do {

    // body of inner do-while-loop

  }while (condition);

  // body of outer do-while-loop

}while (condition);


Loop Control Statements

These control statements change the execution of the loop from its normal execution. The loop control structures are –

1. break statement – It is used to end the loop or switch statement and transfers execution to the statement immediately following the loop or switch.

2. continue statement – It skip some statements according to the given condition.

3. goto statement – It transfer control to the labeled statement.

 
 
