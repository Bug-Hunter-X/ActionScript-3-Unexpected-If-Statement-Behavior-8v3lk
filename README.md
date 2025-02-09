# ActionScript 3 Unexpected If Statement Behavior

This repository demonstrates an unusual bug in ActionScript 3 where an if statement's conditional block doesn't execute as expected, even when the condition appears true. This unexpected behavior is investigated and a solution is proposed.

## Bug Description

The bug involves an if statement within a function where, despite the condition being met, the code inside the if block does not execute.  This might be caused by issues like incorrect data types in the condition or unintended variable scoping. 

## Bug Reproduction

1. Clone the repository
2. Open the `bug.as` file in an ActionScript 3 IDE (e.g., FlashDevelop).
3. Run the code. Observe the unexpected output. The 'Condition met' trace statement should print, but it does not.

## Solution

The solution provided in `bugSolution.as` addresses the issue by addressing the potential causes and ensuring correct data types and scoping.

## Note

This example showcases an uncommon ActionScript error. Understanding the nuances of data types, scoping, and the conditional evaluation process in ActionScript 3 is key to avoiding such issues.