# JAVA School Homework

## English | [中文](https://github.com/plusGo/java-school-2class/blob/master/README-zh_CN.md)

## 1. Why should you have minimum scope for variables?
By minimizing the scope of local variables, you increase the readability and maintainability of your code and reduce the likelihood of error.


## 2. Why should you understand performance of String Concatenation?
To connect N strings, betray repeatedly uses string connection operators. It takes N squares of time. Understanding the performance of string connection can use appropriate string connection methods in appropriate scenarios.

## 3. What are the best practices with Exception Handling?
- Clean up Resources in a Finally Block or Use a Try-With-Resource Statement
- Prefer Specific Exceptions
- Document the Exceptions You Specify
- Throw Exceptions With Descriptive Messages
- Catch the most specific exception first
- Don’t catch Throwable
- Don’t ignore exceptions
- Don’t log and throw
- Wrap the Exception Without Consuming it

## 4. When is it recommended to prefer Unchecked Exceptions?
If a client can reasonably be expected to recover from an exception, make it a checked exception. If a client cannot do anything to recover from the exception, make it an unchecked exception.


## 5. When do you use a Marker Interface?
- When writing methods that only accept Tags
- Markup is for classes and interfaces only


## 6. Why are ENUMS important for Readable Code?
The benefits of using enumerations include: Reduces errors caused by transposing or mistyping numbers. Makes it easy to change values in the future. Makes code easier to read, which means it is less likely that errors will creep into it

## 7. Why should you minimize mutability?
Immutable objects are thread safe, because the state of that object will never be changed, so when different process/thread try to read that object will always get the same result. So it makes concurrent programming a lot cleaner and easier to write.

## 8. What is functional programming?
a functional programming function is like a mathematical function, which produces an output that typically depends only on its arguments. Each time a functional programming function is called with the same arguments, the same result is achieved.

## 9. Why should you prefer Builder Pattern to build complex objects?
- Builder can have multiple variable parameters
- The builder pattern is flexible enough to build multiple objects with a single builder


## 10. Why should you avoid floats for Calculations?
It is not possible to provide a completely accurate calculation result.

## 11. Why should you build the riskiest high priority features first?
The high-priority and high-risk parts play a decisive role in the success and failure of functions or products. Therefore, we should do this part first to ensure the overall success.
