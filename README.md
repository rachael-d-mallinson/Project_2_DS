# Project_2_DS


Infix Expression Parcer - February 2021 - Intro to Data Structures with Java Project 2

TEAM SIX
- Rachael Mallinson
- Sofia Nikas
- Aleksis Martin

Language: Java in eclipse

Design Explanation

For our Infix Expression Parser, we decided to use three steps. First, we  take in the input infix expression as a string labeled “infixExp.” During this process, we take out all of the spaces because we aren’t sure what kind of input we will receive. Then, we use another method (addSpaces) to add spaces into the “infixExp,” separating each of our operands and operators. 
  
Then we  convert our infix expression (infixExp) to a postfix expression. In this method,  we use a stack to store our operands and operators, until it’s time to output them to the postfix expression in the correct order. In order to do this accurately, we set precedences for each of the operators. This helps us to tell the program the correct order that the operators or operands should be placed.  
  
Lastly, we evaluate the postfix expression based on the order of operations made clear by the postfix expression and output it to the standard console. 

How to use the Infix Expression Parcer:
1) Launch the program
2) Name your input file "InfixExpression.txt"
3) Run the program, the result will show in the console
