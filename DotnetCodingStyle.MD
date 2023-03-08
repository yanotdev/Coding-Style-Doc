# C# Coding Style Documentation
## Naming Conventions
* Use PascalCase for class names, struct names, and method names.
* Use camelCase for method parameters and local variables.
* Use all caps with underscores for constants and static readonly fields.
Indentation
* Use 4 spaces for indentation, not tabs.
## Spacing
* Add a space between keywords and parentheses.
* Add a space between the type and variable name when declaring variables.
## Commenting
* Use XML comments for documenting classes, interfaces, methods, and properties.
* Use inline comments for explaining complex or hard-to-understand code.
## Formatting
* Keep lines of code under 120 characters in length.
* Use braces for control statements and loops, even if the body only contains a single statement.
* Use parentheses to group logical expressions and method arguments, even if they are not required.

### Examples
Good Example:
```csharp
public class MyClass
{
    public static readonly int MY_CONSTANT = 42;

    public int MyMethod(string parameter1, int parameter2)
    {
        if (parameter1 == "hello")
        {
            Console.WriteLine(parameter2);
        }

        return parameter2 * 2;
    }
}
```

Bad Example:
```csharp
public class my_class
{
    public static int myConstant = 42;

    public int myMethod(string parameter1,int parameter2) {
        if(parameter1 == "hello") Console.WriteLine(parameter2);

        return parameter2 * 2; }

}
```

## Tools
* Use StyleCop and Visual Studio's built-in code analysis for code linting and formatting.
## Feedback
Please provide feedback and suggestions for improvements to this C# coding style documentation.