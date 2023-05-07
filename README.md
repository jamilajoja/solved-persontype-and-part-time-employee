Download Link: https://assignmentchef.com/product/solved-persontype-and-part-time-employee
<br>
For this lab, you will write the header files and implementation files for 2 classes, which are to be used in the small program that I have provided. The header files must have #ifndef statements, and all the files should be appropriately commented.

The details about the classes are as follows:

• personType

o 2 private member variables to hold the first and last name of a person

o 4 public member functions:

• print – a constant function to print the name of the person .setName – sets the first and last name according to the parameters

• getFirst – constant function which returns the first name . getLast – constant function which returns the last name

o l constructor which sets both the member variables to the empty string if no parameters are provided, otherwise uses the provided information

• Part Time Employee : a public derivation of a personType

o 2 private member variables to hold the payRate and the hours Worked

o 3 public member functions

• print – a constant function to print the last name, first name, and wages for an employee. calculatePay – a constant function which returns the wages for an employee, based on the payRate and hours Worked. . setInfo – Function to set the first name, last name, payRate, and hours Worked according to the parameters.

o 1 Constructor with parameters – Sets the first name, last name, payRate, and hours Worked according to the parameters. If no value is specified, default values of empty strings and the value 0.0 are used for the appropriate variables.