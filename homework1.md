C++ was created to support object-oritented programming(OPP)
An algorithm is a set of instructions for solving a problem.
First:

Desing Concept:Decomposing the Problem 
Breaking down the problem you have into a few subtasks with even smaller substasks would help you reduce the possibility of 
making mistakes.

Information hiding: preconditions and postconditions
Only need to think about what the function does, not how the function does its work.
preconditions is a statement giving the condition that is required to be true when a function is called,
The function is not guaranteed to perform as it should unless the precondition is true.
postcondition is a statement describing what will be true when a function call is completed. (like describing how the correct 
answears look like)
(Always think about those aspects when we need to write the code)


2.1
In this section, the book told us the two parts in a class. The first part is public and the sencod part is private. The coder should break down your problem to smaller problems by using more functions to solve the problem. Also in the function part, if you put a const in the end of a function. It means the function's value itslef couldn't be change. Usually used in getter function.
Also we need scope resolution operatior for example:"throttle::shut_off"

We use constructors to guarantee that every objects is properly initialized.

2.2
Initializing: we need to test the member variable in private in case it may contains garbage. Constructors are a way to solve this problem by providing an initialization function that guaranteed to be called.
Constructors have following properties:
1.If a class has a constructor, then it is called automatically whenever a variable of the class is declared.
2.The name of a constructor must be the same as the name of class.
3.A constructor doesnot have any return values.

