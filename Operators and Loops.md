Operators are the symbols which are used to perform certain operations on the data e.g. addition,
subtraction and comparison etc. There are various types of operators in C, 
which are shown in this section; also, most of these operators are used with decision statements
, therefore usage of these operators are s

hown in
Logical operators

Logical operators are used to perform logic ‘and’, ‘or’ and ‘not’ operations, which are shown in Tabl
e 3.4. Unlike, ‘bitwise logic operators’ these operators do not check the second operator if the first operator 
gives the result e.g. in ‘0 && 1 = 0’, the result does not depend on the value of second operand i.e. ‘1’; because first opera
nd is ‘0’, therefore the result will be zero, whether the second operand is ‘0’ or ‘In the C programming language there 
a number of operators that allow us to construct expressions whose value depends on some condition between the values
of the operands. The following set of four operators, known as the relational operators, are basic examples.

Operator	Meaning
>	Greater than
>=	Greater than or equal to
<=	Less than or equal to
<	Less than



The While Loop Operator

Evaluates y while x is nonzero (true). The condition expression is evaluated at the 
beginning of the while loop, so the loop may never execute. The loop stops iterating 
as soon as the condition is false and it returns the last value calculated in its body on the previous iteration.
Operands
• x is any valid expression or sequence of expressions that can evaluate to 0, frequently a Boolean expression.
• y is any valid expression or sequence of expressions. At least one expression in the loop body must change t
he condition expression, x, so that it becomes false. Otherwise, the loop executes indefinitely.
The For Loop
The for loop has the following syntax:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.


