# Hoisting In JavaScript :

    Hoisting is a phenomenon in Javascript by which we can access the variables and functions even     before declaring or initialising them.
    We can access it without any error.

### Function Declartion : We can declare function in 3 ways: -->

        1. simple way :
                function Greet(){
                    console.log("Hello World");
                }

        2. Giving variable to a function :

                let Greet = function (){
                    console.log("Hello World");
                }

        3. **Using Arrow Function**

                var Greet = () => {
                    console.log("Hello World");
                }
