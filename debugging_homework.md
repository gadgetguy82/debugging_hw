# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
The breakpoint pauses the program when we run it with the debugger.
This allows us to then go through the program line by line so we can check how values change as we the program runs.

2. Does the line of code on a breakpoint run when you start debugging?
No, the line is highlighted and will be the next line of code to run on the next step.

3. How do we debug the next line of code?
We can check the values of the variables and objects to see if they change when expected.

4. What does the step into command do?
The step into command is used to step into a method call so we can step through the lines of code inside the method.

5. What is the difference between evaluate expression and evaluate code fragment?
The evaluate expression can only evaluate one line of code using the objects created thus far.
The evaluate code fragment is used to evaluate multiple lines of code and multiple methods.
You can also create temporary variables in the code fragment mode.
