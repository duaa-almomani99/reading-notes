how javascript makes web pages more interactive
access content and modify content is aspecial feature in java script , programme rules you can specify a asetof stebs for the browser
 to follow , react to events you can specify that ascript should run when aspecfic even has occurred 
 
 - what is ascript and how do i create one 
 a script is a series of instructions  ascript is series of instruction that a computer can follow to a chive agoal , to write ascropt you need to first state your goal 
 and then list tasks that need to be completed in order to achive it 
... desigining a scribt (each invdiviual may be broken down in to a sequence of step when you are raedy to code the scrip, these steps can then be translated in to indiviual line of code 



defining a goal designing the script 
how you might approach a different type of script  this example calculate te coas of name plaque.
a script is a series of instroction that the computer can follow in order to achive a goal 
computers approach tasks in adfferent way than human 

JavaScript's language syntax distinguishes between expressions and statements. These two concepts are subtly different, and you need to understand the difference if you want to understand frameworks like Vue.

In general, an expression is a snippet of code that evaluates to a value. A statement is a snippet of code that performs an action. Wherever JavaScript expects a statement, you can write an expression. But the opposite isn't true: if a framework or the JavaScript runtime expects an expression, you cannot use a statement.

The below code snippets are all expressions. They all evaluate to a value.

Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.
For example, the following code defines a simple function named square:

function square(number) {
  return number * number;
 
}

Function Definition
Before we use a function, we need to define it. The most common way to define a function in JavaScript is by using the function keyword, followed by a unique function name, a list of parameters (that might be empty), and a statement block surrounded by curly braces.

Syntax

The basic syntax is shown here.

<script type = "text/javascript">
   <!--
      function functionname(parameter-list) {
         statements
      }
   //-->
</script>
Example

Try the following example. It defines a function called sayHello that takes no parameters −

<script type = "text/javascript">
   <!--
      function sayHello() {
         alert("Hello there");
      }
   //-->
</script>
