# read 10

## call stack

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

### When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

### Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

### When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

### If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

## error messages

The first thing that indicates you that something is wrong with your code is the (in)famous error message that the one we saw just moments ago, it usually appears on your console

### Reference errors

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

### Syntax errors

 this occurs when you have something that cannot be parsed in terms of syntax

### Range errors

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

### Type errors

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## debugging

Debugging is the process of detecting and removing of existing and potential errors (also called as ‘bugs’) in a software code that can cause it to behave unexpectedly or crash. To prevent incorrect operation of a software or system, debugging is used to find and resolve bugs or defects. When various subsystems or modules are tightly coupled, debugging becomes harder as any change in one module may cause more bugs to appear in another. Sometimes it takes more time to debug a program than to code it.

we can use chrome debugger or vs code to debugge js

# thank you
