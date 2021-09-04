Inheritance is a feature that says if you define a new class giving a reference of some other class then due to inheriting property of python your new class will inherit all attributes and behavior of the parent class.
A Constructor is a special kind of method that have same name as the class in python self variable do the same. It can be used to set the values of the members of an object.

How to define constructor
Syntax:
<img src="images/img1.PNG"><br><br>
How to give values to objects using constructors
<b>Types of constructors : </b><br><br>

default constructor: The default constructor is a simple constructor which doesn’t accept any arguments. Its definition has only one argument which is a reference to the instance being constructed.
parameterized constructor: constructor with parameters is known as parameterized constructor. The parameterized constructor takes its first argument as a reference to the instance being constructed known as self and the rest of the arguments are provided by the programmer.
<br><br>
How to call objects using constructors:<br><br>
Syntax:<br>
Object_name=class_name('variable values',variable values)<br><br>
Program<br><br>
<img src="images/img2.PNG"><br><br>
Output<br>
1000<br><br>
How to inherit a class<br><br>
Syntax:<br><br>
class class_name(parent class name)<br><br>
How to check whether it is inherited or not<br><br>
Syntax:<br><br>
Object_name = inherited_class_name('variable1,variable2')<br>
print(Object_name.variable1)<br>
Output: variable value.<br>
Program<br><br>
<img src="images/img3.PNG"><br><br>
Output<br><br>
Geek1 False<br>
Geek2 True

