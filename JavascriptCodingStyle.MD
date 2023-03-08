# JavaScript Coding Style Documentation

## Naming Conventions
* Use camelCase for variable names and function names.
* Use PascalCase for class names and constructor functions.
* Use all caps with underscores for constants.
* Use kebab-case for HTML attributes and CSS classes.

## Indentation
* Use 2 spaces for indentation, not tabs.

## Spacing
* Add a space between keywords and parentheses.
* Add a space between the function name and opening parenthesis when declaring functions.
* Add a space between the colon and type when declaring type annotations.

## Commenting
* Use JSDoc comments for documenting functions, classes, methods, and properties.
* Use inline comments for explaining complex or hard-to-understand code.

## Formatting
* Keep lines of code under 80 characters in length.
* Use braces for control statements and loops, even if the body only contains a single statement.
* Use parentheses to group logical expressions and method arguments, even if they are not required.
* Use a comma at the end of the last item in an object or array declaration.

### Examples
Good Example:
```javascript
class MyClass {
  static MY_CONSTANT = 42;

  myMethod(parameter1, parameter2) {
    if (parameter1 === "hello") {
      console.log(parameter2);
    }

    return parameter2 * 2;
  }
}
```

Bad Example:
```javascript
class my_class {
  static myConstant = 42;

  myMethod(parameter1,int parameter2) {
    if(parameter1 == "hello") console.log(parameter2);

    return parameter2 * 2;
  }
}
```

## Tools
* Use ESLint and Prettier for code linting and formatting
## Feedback
Please provide feedback and suggestions for improvements to this JavaScript coding style documentation