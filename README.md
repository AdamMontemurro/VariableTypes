# Variables

When naming variables in Java it is a common practice to use camel casing. 

Examples: <br>
variableOne  <br>
myAge  <br>
camelCasedVariableInteger <br>
*Remember variables are case sensitive!*

You cannot start a variable with a number. For clarity, is good to use full words when naming variables rather than ambigious abbreviations.

Declarations for variables in JAVA start by specifying the variable type. Let's printout our age in the console. 

First we have to declare an integer that we will call "age". 
![Declaring Variable](https://i.imgur.com/zwD1JDY.png) <br>
You cannot use an uninitialized variable in JAVA. If you remove the line assigning a value to "age" and run the code you will recieve an error stating "The local variable age may not have been initialized". To avoid this you can both declare and initialize a variable on the same line. 
![An uninitialized variable](https://i.imgur.com/aypbN5R.png) <br>

You can reasign the value of a variable multiple times. JAVA will use the latest value declaration.

The console will print out "I am 31 years old."

Keep in mind that you cannot declare the same variable twice.
![Variable Declared Twice](https://i.imgur.com/71mfdS4.png)<br>
You may have noticed there are two set's of curly braces. Code inside a set of curly braces is a "code block".

The first set belongs to the HelloWorld Class. They mark the start and the end of the class. 

The second set marks the start and end of the "main" method. If you notice the main method is contained within the HelloWorld class code block. This means any variable inside the method is a local variable, or only available inside the method. 
However, if we declared our age variable inside the HelloWorld code block it would be available to anything inside the class. To do this we must declare the variable as a static. 

If you do not give your variable a value at the class level, JAVA will assign a default value. Try to declare age without a value and see what prints out. 

What happens if you redeclare the variable inside the main method code block? Which value will be read? 


