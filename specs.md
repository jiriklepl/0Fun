# SPECS

This is 0Fun.

## Objects

### Definition

Objects are created using the `struct` keyword followed by the name of the defined object and then followed by brace-enclosed list of definitions of the members of the object.

#### Struct methods

All functions defined inside the definition of an object `O`, struct methods (or object methods), have a non-spoken `this`-specified readonly argument of the type `O *` called `this`.

## Functions

### `this` specifier

At maximum, one pointer-typed function argument can have the `this` specifier, then it is the implicit argument for all functions carrying a `this` argument if such an argument is ommited in their calls.

It also allows the function to be given this argument using the `argument.function` syntax.
