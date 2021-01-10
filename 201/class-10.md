# Reading 10: Debugging

> debugging ? so like bed bugs? or like a hornets nest? - The guy at the corner store.

## Reading 10: Debugging notes

+ JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.
+ To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:
+ The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.
+ Each time a script enters a new execution context, there are two phases of activity:
+ 1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined
+ 2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements
+ In the interpreter, each execution context has its own vari ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's vari ables object.
+ If a variable is not found in the variables object for the current execution context, it can look in the variables object of the parent execution context. But it is worth knowing that looking further up the stack can affect performance, so ideally you create variables inside the functions that use them.
+ if you are anticipating that something in your code may cause an error, you can use a set of statements to handle the error
+ Error objects can help you find where your mistakes are and browsers have tools to help you read them.
+ If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.
+ Sometimes, an error may occur in the script for a reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code.
+ JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
[Back to main](README.md)