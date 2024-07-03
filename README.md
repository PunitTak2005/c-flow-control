# go to statement
to understand go to statement




The goto statement is a jump control statement that allows us to transfer control of the other part of the program with the help of a label.

Syntax :

goto label;
..........
..........
label:
statement;
..........

 
Working of goto statement

The label is an identifier. When goto label; is encountered, the control of program jumps to label: and executes the code below it
label can be used anywhere in that function where the goto statement is used.
Why we Avoid goto Statement

The goto statement gives power to jump to any part of program but, makes the logic of the program complex and tangled.
The problem with using goto statement is that it is easy to develop program logic that is very difficult to understand, even for the original author of the code.
In modern programming, goto statement is considered a harmful construct and a bad programming practice.
It is easy to get caught in an infinite loop if the goto point is above the goto call.
The goto statement can be avoided in most of C program with the use of break and continue statements.
