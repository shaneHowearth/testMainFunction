# testMainFunction
Trivial example of testing the main function with an example

It is possible to test the main function in a Go program, the only requirement is that the test be in the main package.

Note: This is NOT best practice, it's just a PoC.

main is just like any other function, in that it can be called by any other function in the same package. 
It does have some special qualities though, it is not exportable, and it is the function that the compiler is hardwired to execute when the application is run.
