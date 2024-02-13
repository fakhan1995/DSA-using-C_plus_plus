Variables

A variable is a container (storage area) used to hold data.
Each variable should be given a unique name (identifier).
int a=2;
Here a is the variable name that holds the integer value 2.
The value of a can be changed, hence the name variable.
There are certain rules for naming a variable in C++

1. Can only have alphabets, numbers and underscore.
2. Cannot begin with a number.
3. Cannot begin with an uppercase character.
4. Cannot be a keyword defined in C++ language (like int is a keyword).

Fundamental Data Types in C++

Data types are declarations for variables. This determines the type and size of
data associated with variables which is essential to know since different data
types occupy different size of memory.

Data Type Meaning Size (in Bytes)
int Integer 4
float Floating-point 4
double Double Floating-point 8
char Character 1
wchar_t Wide Character 2
bool Boolean 1
void Empty 0

1. int
   􀁸 This data type is used to store integers.
   􀁸 It occupies 4 bytes in memory.
   􀁸 It can store values from -2147483648 to 2147483647.
   Eg. int age = 18

2. float and double
   􀁸 Used to store floating-point numbers (decimals and exponentials)
   􀁸 Size of float is 4 bytes and size of double is 8 bytes.
   􀁸 Float is used to store upto 7 decimal digits whereas double is used
   to store upto 15 decimal digits.
   Eg. float pi = 3.14
   double distance = 24E8 // 24 x 108
3. char
   􀁸 This data type is used to store characters.
   􀁸 It occupies 1 byte in memory.
   􀁸 Characters in C++ are enclosed inside single quotes 􀍚 􀍚.
   􀁸 ASCII code is used to store characters in memory.
   Eg char ch ='a';

4. bool
   􀁸 This data type has only 2 values 􀍴 true and false.
   􀁸 It occupies 1 byte in memory.
   􀁸 True is represented as 1 and false as 0.
   Eg. bool flag = false

C++ Type Modifiers

Type modifiers are used to modify the fundamental data types.

Data Type Size (in Bytes) Meaning
signed int 4 used for integers (equivalent to int)
unsigned int 4 can only store positive integers
short 2 used for small integers (range -32768 to 32767)
long at least 4 used for large integers (equivalent to long int)
long long int 8 used for very large integers (equivalent to long
long int).
unsigned long
long
8 used for very large positive integers or 0
(equivalent to unsigned long long int)
long double 8 used for large floating-point numbers
signed char 1 used for characters (guaranteed range -127 to 127)
unsigned char 1 used for characters (range 0 to 255)

Derived Data Types

These are the data types that are derived from fundamental (or built-in) data
types. For example, arrays, pointers, function, reference.

User-Defined Data Types

These are the data types that are defined by user itself.
For example, class, structure, union, enumeration, etc.
