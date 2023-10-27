# Python-week1
Day1

Daily Notes - History of Python
 Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. It is a relatively simple language that includes a standard library that provides modules for a large number of processes that programs deal with. This approach keeps Python simple yet reliable programming language.

Python has an easy-to-use syntax that is focused on the programmer who must type in the program, read what was typed, and provide formal documentation for the program. Many languages have syntax focused on developing a simple, fast compiler; but those languages may sacrifice readability and can be more difficult to write. Python strikes a good balance between fast compilations and readability, and it is easier to write applications.

Python is implemented in C and relies on the extensive, well understood, portable C libraries. It fits seamlessly with UNIX, Linux, and POSIX environments. Since these standard C libraries are widely available for the various MS-Windows variants, and other non-POSIX operating systems, Python runs similarly in all environments. The Python programming language was created based on lessons learned during language and operating system support. Python is built from concepts in the ABC and Modula-3 languages.
Daily Notes - Invoking the Interpreter
 Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. It is a relatively simple language that includes a standard library that provides modules for a large number of processes that programs deal with. This approach keeps Python simple yet reliable programming language.

Python has an easy-to-use syntax that is focused on the programmer who must type in the program, read what was typed, and provide formal documentation for the program. Many languages have syntax focused on developing a simple, fast compiler; but those languages may sacrifice readability and can be more difficult to write. Python strikes a good balance between fast compilations and readability, and it is easier to write applications.

Python is implemented in C and relies on the extensive, well understood, portable C libraries. It fits seamlessly with UNIX, Linux, and POSIX environments. Since these standard C libraries are widely available for the various MS-Windows variants, and other non-POSIX operating systems, Python runs similarly in all environments. The Python programming language was created based on lessons learned during language and operating system support. Python is built from concepts in the ABC and Modula-3 languages.

Day2

Daily Notes - Introduction to Variables
 n Python identifiers are case sensitive, so for example, firstName, FirstName, FIRSTNAME, and firstname are four different identifiers. A second rule is that variables cannot have the same name as Python’s keywords. We can find out what keywords are in Python, by using the function called dir(). If this function is called with the __builtins__ attribute, it returns a list of Python’s built-in attributes.
Daily Notes - Using variables
 Python has a powerful feature regarding the assignment. A variable is assigned automatically to an appropriate data type. For example, Python automatically assigns a variable to a string data-type, if an input or value is given that contains letters or words. Values of the same type can be manipulated together. Sometimes Python finds a way to manipulate values into a common type by casting the values automatically. There are cases where values need to be cast explicitly.
Daily Notes - Casting
 Implicitly: The compiler automatically casts a value from one data type to another when assured that there will be no data loss.
For example. casting from an integer variable to a floating-point variable or casting from an integer variable to another integer variable
Explicitly: A value cannot be automatically cast from one data type to another if it will result in data loss. Extra code has to be written to ensure that the value stays the same and only the data type changes.

Day3

Daily Notes - Integers
 integers are numbers. Numbers can have negative and positive values. Integers are always whole numbers. Integers include negative and positive numbers. The only factor that determines the range of an integer variable is the amount of memory a machine has available.
Daily Notes - Floating point numbers
 Floating point numbers are better known as floats. Float is the data type that manages numbers with decimal places with very accurate precision. The float data type can be called as a function with zero or 1 argument of any data type. If no argument is given, then float returns 0.0. If an argument is given, an attempt will then be made to convert the value to a float data type, but this does not mean it is always possible. For example, float("21.765") will be converted to a float, but float("FF909A") will raise an exception.
A string value cast to a float must contain only numbers and only one occurrence of the dot (.) character.
Daily Notes - Unpacking Argument Lists
 Strings are represented by the immutable (unchangeable) str data type. Strings are a sequence of Unicode characters which form a single manageable string. The str data type can be called to create a string; when there is no argument supplied, it returns an empty string. s = str("") is the same as s = str(), when an argument is passed to the string method that is not a string value, it is passed as a string representation of the type supplied: s = str(17.2354), is the same as s = str("17.2354"). The string function is often used to convert other data types to strings.
Daily Notes - Lambda Expressions
 Small anonymous functions can be created with the lambda keyword. This function returns the sum of its two arguments: lambda a, b: a+b. Lambda functions can be used wherever function objects are required.
They are syntactically restricted to a single expression. Semantically, they are just syntactic sugar for a normal function definition. Like nested function definitions, lambda functions can reference variables from the containing scope
Daily Notes - Conventions about the content and formatting of documentation strings
 The first line should always be a short, concise summary of the object’s purpose. For brevity, it should not explicitly state the object’s name or type, since these are available by other means (except if the name happens to be a verb describing a function’s operation). This line should begin with a capital letter and end with a period.

If there are more lines in the documentation string, the second line should be blank, visually separating the summary from the rest of the description. The following lines should be one or more paragraphs describing the object’s calling conventions, its side effects, etc.

The Python parser does not strip indentation from multi-line string literals in Python, so tools that process documentation have to strip indentation if desired. This is done using the following convention. The first non-blank line after the first line of the string determines the amount of indentation for the entire documentation string.
Activity 1 - Consolidating Learnings
 The AND gate is a basic digital logic gate that implements logical conjunction (∧) from mathematical logic – AND gate behaves according to the truth table. A HIGH output (1) results only if all the inputs to the AND gate are HIGH (1). If not all inputs to the AND gate are HIGH, LOW output results. The function can be extended to any number of inputs.


 Day4

 Daily Notes - Introduction to operators
 Operators are used to testing conditions and manipulating values. Most statements contain expressions: an example of an expression is: 2 + 3. When two objects of a different type, like str and int, are compared they are never equal, except for different numeric types like int and float which can be equal.
Daily Notes - Using Operators
 Floats can use all of int’s operators and functions. ints can use float’s operators and functions, but in some cases it will not make sense to use them with ints because some functions would just return the value they were passed. For example, math.trunc(a) would return a. Some operators can also be used with other data types, e.g. str.
Daily Notes - Activity 1
 Here's how the program works:

It takes the user's input in liters.
It calculates the number of bottles by multiplying the input by 1000 (to convert liters to milliliters) and dividing by 500 ml (the size of a bottle).
It calculates the remaining water by subtracting the water used to fill the bottles from the total input.
It displays the number of bottles that can be filled and the remaining water in liters.
When you run the program, it will give you the desired output as described in your question.
Daily Notes - Activity 2
 Here's how the program works:

It takes the input from the user in milliliters.
It converts the released milliliters to liters by dividing by 1000 (since 1,000 milliliters = 1 liter).
It calculates the remaining liters by subtracting the released liters from the capacity of the Albasini Dam, which is 1 megalitre (1,000,000 liters).
It calculates the percentage of liters left by dividing the remaining liters by the total capacity and multiplying by 100.
It generates and displays the water conservation report, including the released liters, remaining liters, and the percentage left.
