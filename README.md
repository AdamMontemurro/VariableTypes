# Variables

When naming variables in Java it is a common practice to use camel casing. 

Examples:  
- variableOne  
- myAge  
- camelCasedVariableInteger  

*Remember variables are case sensitive!*

You cannot start a variable with a number. For clarity, is good to use full words when naming variables rather than ambigious abbreviations.

Let's printout our age in the console.  

First, let's make our class, we will call it HelloWorld for now.  

![Class](https://i.imgur.com/WoTU3wl.png)  

Let's define our main method inside the HelloWorld class.  

![Main Method](https://i.imgur.com/ynstIsq.png)  

Next, we have to declare an integer that we will call "age". Give our variable a value. Declarations for variables in JAVA start by specifying the variable type.    

![Declaring Variable](https://i.imgur.com/zwD1JDY.png)  

Let's make sure we are printing our age.  

![Print our age](https://i.imgur.com/m4iOezU.png)  

*You cannot use an uninitialized variable in JAVA. If you remove the line assigning a value to "age" and run the code you will recieve an error stating "The local variable age may not have been initialized".*  

![Uninitialized variable](https://i.imgur.com/Xrxt88J.png)  
![Error Message](https://i.imgur.com/hHpjjpq.png)  

To avoid this you can both declare and initialize a variable on the same line.   

![Initialized and value assigned on the same line](https://i.imgur.com/ZWG3OlN.png)  

You can reasign the value of a variable multiple times. JAVA will use the latest value declaration.  

![Value changed](https://i.imgur.com/ha33ekF.png)  

The console will print out "I am 31 years old."  

Keep in mind that you cannot declare the same variable twice.  
![Variable Declared Twice](https://i.imgur.com/71mfdS4.png)  

You may have noticed there are two sets of curly braces. Code inside a set of curly braces is a "code block".  
![Code Block](https://i.imgur.com/r8thk3Q.png)  

The first set belongs to the HelloWorld Class. They mark the start and the end of the class. The second set marks the start and end of the "main" method. If you notice the main method is contained within the HelloWorld class code block. This means any variable inside the method is a local variable, or only available inside the method.  
![Code Block Scopes](https://i.imgur.com/2XAkhgx.png)  
However, if we declared our age variable inside the HelloWorld code block it would be available to anything inside the class. To do this we must declare the variable as a static.  

![Declare Variable in Class code block](https://i.imgur.com/LCp0oE1.png)  

If you do not give your variable a value at the class level, JAVA will assign a default value. Try to declare age without a value and see what prints out. 

What happens if you redeclare the variable inside the main method code block? Which value will be read? 


