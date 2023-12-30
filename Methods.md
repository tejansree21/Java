# METHODS IN JAVA

METHODS ARE THE ACTIONS THAT ARE EXECUTED TO GENERATE RESULTS.
(Methods in other languages are known as Functions.)

Based on the "static" keyword the methods are categorized into two types:-
  a. Static Methods
  b. Non-Static Methods

a. Static Methods
=> The methods that are declared with the "Static" keyword are known as Static Methods.
=> These static methods will get memory within the class and can be accessed with class_name.

Structure of the static method:- 
static return_type method_name (parameter_list)
{
  //method body
}

=> Static methods can access static variables directly but cannot access instance variables directly.

Types of Static Methods
  a. pre-defined static methods
  b. user-defined static methods

a. pre-defined static methods
=> The static methods that are defined and available in JavaLib are known as pre-defined static methods.

b. user-defined static methods
=> The static methods that are defined by the programmer are known as user-defined static methods.

b. Non-Static Methods
=> The methods that are declared without the "Static" keyword are known as Non-Static Methods.
=> These methods will get memory within the object and can be accessed with object_name.

Structure of the Non-Static Method
return_type Method_name(parameter_list)
{
  // Method body
}

=> Instance methods can access both class variables and Instance variables directly.


