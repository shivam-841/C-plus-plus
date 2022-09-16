main() is not actually the entry point of the program, though the standard states that it is the designated start.

It is the only function that could omit the return statement.

Another interesting property of the main() function is that its return type cannot be deduced automatically.

extras-------------------------------------

The constexpr specifier declares that the value of the function is possible to evaluate at compile time. The main() function cannot be declared as constexpr.
