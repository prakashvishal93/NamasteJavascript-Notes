# Execution Context :

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

# Call Stack :

    Call Stack is like a stack and everytime in the bottom of the stack, we have our Global Execution Content.
    That means whenever a javascript Program is run, this call stack is populated with the global execution Context.
    And whenever a function is invoke or a new execution Content is created, this execution context is put in the stack.

        Call Stack maintains the Order of Execution of Execution context.

        Other Names of Call Stack :
            1. Execution Context Stack
            2. Program Stack
            3. Control Stack
            4. Runtime Stack
            5. Machine Stack
