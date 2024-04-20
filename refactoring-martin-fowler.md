
### Chapter 1 Refactoring: A First Example

- Motivation for refactoring:
	- When you have to add a feature to a program but the code is not structured in a convenient way, first refactor the program to make it easy to add the feature, then add the feature.
	- It is the need for changing existing code to support additional features that drives the need to perform refactoring. If the code works and doesn't ever need to change, it is perfectly fine to leave it alone.
- First step in refactoring: ensure to have a solid set of self-checking tests for that section of code so that if refactoring breaks something inadvertently, it is readily caught.
- Refactor the programs in small steps so that mistakes can be easily debugged.
- *compile-test-commit*: Commit the code to version control after each successful refactoring. Can squash the changes into more significant commits if required before pushing.

> Any fool can write code that a computer can understand. Good programmers write code that humans can understand.

- Good code should clearly communicate what it is doing and variable names are a key to clear code.
- If refactoring introduces performance slow-downs, finish refactoring first and do performance tuning afterwards - this may lead to reversing some the refactoring done earlier.