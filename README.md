The Type System represents the different types of values supported by the language. The Type System checks validity of the supplied values, before they are stored or manipulated by the program. This ensures that the code behaves as expected. The Type System further allows for richer code hinting and automated documentation too.

Rust is a statically typed language. Every value in Rust is of a certain data type. The compiler can automatically infer data type of the variable based on the value assigned to it.
Declare a Variable

Use the let keyword to declare a variable.


In the above example, data type of the variables will be inferred from the values assigned to them. For example, Rust will assign string data type to the variable company_string, float data type to rating_float, etc.

The println! macro takes two arguments −

    A special syntax { }, which is the placeholder
    The variable name or a constant

The placeholder will be replaced by the variable’s value
The output of the above code snippet will be −

company name is: TutorialsPoint
company rating on 5 is:4.5
company is growing: true
company icon is: ♥
