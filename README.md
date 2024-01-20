# Create and run simple C# console applications (Get started with C#, Part 2) 

Your goal was to install and configure a development environment that meets your coding requirements for C#.

You've installed Visual Studio Code and a tour of the user interface demonstrated a logical layout that is consistent with industry standards. You were able to configure extensions that make Visual Studio Code an even more powerful tool for C# code development. You also installed the .NET SDK to provide compiler and runtime support, and support for .NET command line interface commands.

-  Download and install Visual Studio Code
-  Configure Visual Studio Code
  -  install the C# extension
  -  install the.NET Core SDK
  -  install the.NET Core runtime
  -  install the.NET Core command line interface
  -  install the C# language support for Visual Studio Code
  -  configure Visual Studio Code to use the.NET Core command line interface
-  install the.NET SDK
-  Create and run a simple C# console application 
  ```
    dotnet new console -o --name HelloWorld
  ```
- Build and run the application
  ```
    dotnet build
  ```
-  Run a C# console application
  ```
    dotnet run
  ```


# The C# programming language allows you to build many types of applications, like:

- Business applications to capture, analyze, and process data
- Dynamic web applications that can be accessed from a web browser
- Games, both 2D and 3D
- Financial and scientific applications
- Cloud-based applications
- Mobile applications

In this module, you'll:

- Write your first lines of C# code.
- Use two different techniques to print a message as output.
- Diagnose errors when code is incorrect.
- Identify different C# syntax elements like operators, classes, and methods.

# C# is
- C# is a case-sensitive 
- Use double quotation marks to define a string
  ```
  Console.WriteLine(''Hello World!'');
  ```
  Console part is called a class
  Classes "own" methods; or you could say that methods live inside of a class
  WriteLine() part is called a method
   The parentheses are known as the method invocation operator
   the semicolon is the end of statement operator

The difference between Console.Write and Console.WriteLine
- Console.Write is used to print a message without a new line
- Console.WriteLine is used to print a message with a new line
- syntax: rules for writing C# code is called syntax.