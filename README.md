# JSONPARSER
In this json parser a string to be validated has been hardcoded and Collections have been used to implement the Stack Data Structure.

The hardcoded String is iterated from left to right and and balanced parenthesis is checked for validation of json.
Also it check misplaced "double quotes", "colons", "comma" and outputs "invalid" json if the syntax is not correct.

printStack() method is used to check whether the stack is empty at the end of iteration.If Stack is empty then it means that JSON is valid otherwise it is invalid.