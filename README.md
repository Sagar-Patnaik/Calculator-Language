Name: Sagar Patnaik and Dhanesh Akolu
Stevens Login: spatnaik@stevens.edu and dakolu@stevens.edu

Public GitHub Repo URL

The URL of my public GitHub repo is: https://github.com/Sagar-Patnaik/Calculator-Language

Hours Spent on the Project:
I estimate that I spent around 50 hours on the project.

Description of code:
This Python program that takes an input mathematical expression as a string and tokenizes it, evaluates it, and assigns variables if present.

The parse_expression() function is responsible for tokenizing the input expression by first splitting it into individual tokens and then categorizing them as either numbers, operators, variables, or keywords such as "print." This function also handles variable assignment and prints statements.

The tokenize() function then takes the tokens generated by parse_expression() and creates a stack of operators and operands, using a precedence dictionary to determine the order of operations.

The evaluate_expression() function evaluates the expression based on the postfix notation generated by the tokenize() function. This function utilizes a stack to perform arithmetic operations and uses the operators dictionary to map the operator symbols to their corresponding operations.

Lastly, the main() function is responsible for taking input from the user and printing the result. This function calls parse_expression(), tokenize(), and evaluate_expression() functions to tokenize and evaluate the expression, and then prints the result.

The global variables, global_vars and print_flag, keep track of variables assigned and whether a print statement has been executed or not. The program raises a ValueError if there is an invalid input or a parse error.


Description of Testing Methodology
To test my code, I created several test cases covering a wide range of scenarios. I also used a diff tool to compare the expected output with the actual output of the program.

Bugs or Issues Encountered
While working on the project, I encountered several bugs and issues, especially in the operators section. Despite my best efforts, I was unable to resolve all of them.

Example of a Difficult Bug and its Resolution
One particularly difficult bug I encountered involved an operator that was returning incorrect results. After several hours of troubleshooting, I realized that the issue was caused by a typo in the operator's code. Once I corrected the typo, the operator worked correctly.

Extensions
Comments feature implemented.
