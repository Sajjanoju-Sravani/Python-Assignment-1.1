Q1. What is different between List and Tuple?
Ans: Lists and Tuples store one or more objects or values in a specific order. The main difference between lists and tuples are list is mutable and tuples are immutable. List has [] square brackets and tuple has Parantheses().

Q2. What are the built-in type does python provides?
Ans: There are mutable and immutable types of python built-in types
mutable built-in types are list, sets, dictionaries
immutable built-in types are strings, tuples, numbers

Q3. which are the different types of operators in python?
  Ans: following is a list of operators in python:
    Arithmetic operators
    Relation operators
    Assignment operators
    Logical operators
    Membership operators
    Identity operators
    Bitwise operators

Q4. How to overload constructors or methods in python?
Ans: python's constructor: __init__() is a first method of a class. Whenever we try to instantiate a object __init__() is automatically invoked by python to initialize members of an object

Q5. What do you understand by __init__() method in python? 
Ans: __init__ is a special method in python classes is a constructor method for a class __init__ is called when ever an object of the class is constructed

Q6. Explain python functions ?
Ans: A function is a section of program or a block of code that is written once and can be exected whenever required in the program
There are two types of functions:
Built-in functions
User defined functions

Q7. Which are the file related libraries/modules in python?
Ans: python provides libraries/modules with functions that facilitate you to manipulate text files and binary files on file system by using these libraries,you can create files, update their contents, copy and delete files. These libraries are: os,os.path,and shutil.os and os.path: os and os.path libraries include functions for accessing the file system. shutil: shutil library is used to copy and delete the files

Q8. Deep copy vs shallow copy ?
Ans:Deep copy : creates new separate copy of the objects and its elements any change made in new copy doesn't reflect on original one
    shallow copy : creates copy of the object but rather than copying the elements of object it copies the refernces to their memory address any change made to the copy reflects in the original
                   
Q10.What are local variables and global variables in Python?
Ans: Global Variables: Variables declared outside a function or in global space are called global variables.  These variables can be accessed by any function in the program.
     Local Variables: Any variable declared inside a function is known as a local variable. This variable is present in the local space and not in the global space.

Q11. what is python zip() function?
Ans: The python zip() function is used to transform multiple lists ie list1,list2,list3 etc into a single list of tuples by taking the corresponding elements of the lists that are passed as parameters.
   
Q12. what is python's parameter passing mechanism ?
Ans: There are two parameter passing mechanism in python:
 pass by references
 pass by value
 by default, all the parameters(arguments) are passed by reference to the functions thus, it you change the value of the 
 parameter within a function the change is reflected in the calling function.
 The pass by value is that whenever we pass the arguments to functions that are of type say numbers, strings, tuples. 
 this is because of the immutable nature of them.

Q13. what is pep 8?
Ans: pep 8 is a coding convention which specifies a set of guidelines, about how to write your python code more readable

Q14. what do you mean by python literals?
Ans: python literals can be defined as data which are given in a variable or constant. there are 5 types of literals in python:
  There are 5 types of literals in python:
   String literals,
   Numeric literals,
   Boolean literals, 
   Special Literals,
   literal collections

Q15. What is web scraping ? how would you achieve web scraping in python?
Ans: web scrapping is a method of extracting the large amounts of information which is available on the web sites and saving it onto the local machine or onto the database tables.
  In python following are some modules for web scraping:
  Urllib2
  scrappy
  pyquery
  Beautifulsoap etc.

Q16. What do you understand by inheritance in python? give an example of it ?
Ans: one class acquiring the property of another class.
    Eg: In a family tree, traits such as hair color and poor eyesight are passed from generation to generation
   
Q17. What is a lambda function ? 
Ans: Anonymous function, ie a function without a name.
    lambda arguments: expression

Q18. What is pickling and unpickling ?
Ans: pickling --> converting an object in memory to a byte stream that can be stored on a disk or sent over a network.
     Unpickling--> loading a pickled file back into a python program.
       
Q19. What are decorators in python?
Ans:  Extending the functionalities of existing functions without modifying them.

Q20. What are classes and objects in python?
Ans: class is an blue print,and objects to be real world entites which are defined and created from classes
