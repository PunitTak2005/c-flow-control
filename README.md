# switch case
to understand switch cases
Switch Statement

The switch statement is used to execute different parts of code based on the value of an expression.

 

In simple words, Switch statements are helpful when we have a set of multiple conditions and the user needs to select one of them based on the matching condition.

 

Syntax:

switch (expression)

​{

  case constant1:

  // statements

  break;

  case constant2:

  // statements

  break;

  .

  .

  default:

  // default statements

}

 

How does the switch statement work?

The expression is evaluated once and compared with the values of each case label. If the any case matches then the block of code associated with that case is executed.
Then, the break is encountered, the execution of that case stops and the switch statement terminates.
However, if any case does not match, then default case is executed.
We can do the same thing with the if...else..if ladder. However, the syntax of the switch statement is cleaner and much easier to read and write.
The default keyword is responsible for executing the piece of code if no matching case labels are found.
The data type of case labels of the switch statement can be either an integer or character type.
The case label can be either a constant variable or a constant expression.
 

 

Note : Switch case statement is a control statement that is regarded as a substitute for if-else statements.

If we do not use break, all statements after the matching label are executed.

The default case inside the switch statement is optional.

 

Points to Remember

The expression provided in the switch must be a constant value otherwise it is invalid.
Duplicate case values are not allowed.
The default statement is optional. Even if the switch case statement do not have a default statement, it would work without any problem.
The break statement is used to take control out of the loop otherwise all the cases before a break would be executed.
break statement is used inside the switch to terminate a statement sequence. When a break statement is reached , the switch terminates, and the flow of control jumps to next line following the switch statement.
The break statement is optional. If omitted, execution will continue on into the next case. The flow of control will fall though to subsequent cases until a break is reached.
The switch statement can also be nested, which means you have switch statements inside another switch.
