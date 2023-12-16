Execution Context :
    -> Everything in javascript happens inside a Execution Context. 
    -> It is like a big box. and it has two component in it. 

    -> First component is called - Memory which holds key value pairs. This is also known as Variable   Environment.

    -> Second component is called - Code component. This is the place  where code is execute one line at a time. It is also called Thread of Execution.


    This Execution Content is created in two phase: 
        1. Memory Creation Phase : Critical Phase ---> 
            In this phase, we were allocating memory to all the Variable and functions inside this global space. 
            We allocate Varible with undefined and incase of function we just copy the code of whole function.

        2. Code Execution Phase : 
            Now the Javascript Program is executed line by line. It replace undefined with the value given. And simpliarly it invoke the function.





JAVASCRIPT: 
    Javascript is a synchronous Single-threaded Language. 

    Single threaded means, javascript can execute one command at a time.

    Synchronous-threaded language means, Javascript can only execute one command at a time and  in a specific order. which means it can only go to the next line once the current line is finished executing.
