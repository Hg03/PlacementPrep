<details>
<summary>What is OOPS and its concepts ? </summary>
<br>
OOPS is abbreviated as Object Oriented Programming system in which programs are considered as a collection of objects. Each object is nothing but an instance of a class.
Following are the concepts of OOPS:<br>
1.  Abstraction<br>
2.  Encapsulation<br>
3.  Inheritance<br>
4.  Polymorphism<br>
<br><br>
</details>

<details>
<summary>What is class, object, encapsulation, polymorphism, inheritance, manipulators, </summary>
<br>
- A **class** is simply a representation of a type of object. It is the blueprint/plan/template that describes the details of an object.** <br><br>
- An **object** is an instance of a class. It has its own state, behavior, and identity.<br><br>
- **Encapsulation** is an attribute of an object, and it contains all data which is hidden. That hidden data can be restricted to the members of that class.Levels are Public, Protected, Private, Internal, and Protected Internal.<br><br>
- **Polymorphism** is nothing but assigning behavior or value in a subclass to something that was already declared in the main class. Simply, polymorphism takes more than one form.<br><br>
- **Inheritance** is a concept where one class shares the structure and behavior defined in another class. If Inheritance applied to one class is called Single Inheritance, and if it depends on multiple classes, then it is called multiple Inheritance.<br><br>
- **Manipulators** are the functions which can be used in conjunction with the insertion (<<) and extraction (>>) operators on an object. Examples are endl and setw.<br><br>
</details>

<details>
<summary>What is constructor ?</summary>
<br>
A constructor is a method used to initialize the state of an object, and it gets invoked at the time of object creation. Rules for constructor are: <br><br>- Constructor Name should be the same as a class name.<br><br>- A constructor must have no return type.<br><br>
</details>

<details>
<summary>What is destructor ?</summary>
<br>
A destructor is a method which is automatically called when the object is made of scope or destroyed. Destructor name is also same as class name but with the tilde symbol before the name.
</details>

<details>
<summary>What is virtual function ?</summary>
<br>
A virtual function is a member function of a class, and its functionality can be overridden in its derived class. This function can be implemented by using a keyword called virtual, and it can be given during function declaration.<br><br>A virtual function can be declared using a token(virtual) in C++. It can be achieved in C/Python Language by using function pointers or pointers to function.
</details>

<details>
<summary>What is friend function ?</summary>
<br>
A friend function is a friend of a class that is allowed to access to Public, private, or protected data in that same class. If the function is defined outside the class cannot access such information. <br> A friend can be declared anywhere in the class declaration, and it cannot be affected by access control keywords like private, public, or protected.
</details>

<details>
<summary>What is function Overloading ?</summary>
<br>
Function overloading is a regular function, but it is assigned with multiple parameters. It allows the creation of several methods with the same name which differ from each other by the type of input and output of the function. 
</details>

<details>
<summary>What is Operator Overloading ?</summary>
<br>
Operator overloading is a function where different operators are applied and depends on the arguments. Operator,-,* can be used to pass through the function, and it has its own precedence to execute.
</details>

<details>
<summary>What is abstract class ?</summary>
<br>
An abstract class is a class which cannot be instantiated. Creation of an object is not possible with an abstract class, but it can be inherited. An abstract class can contain only an Abstract method. Java allows only abstract method in abstract class while other languages allow non-abstract method as well.
</details>

<details>
<summary>What is the use of finalize method ?</summary>
<br>
Finalize method helps to perform cleanup operations on the resources which are not currently used. Finalize method is protected, and it is accessible only through this class or by a derived class.
</details>

<details>
<summary>What are the different types of arguments ?</summary>
<br>
A parameter is a variable used during the declaration of the function or subroutine, and arguments are passed to the function body, and it should match with the parameter defined. There are two types of Arguments. <br><br> *  Call by Value – Value passed will get modified only inside the function, and it returns the same value whatever it is passed into the function.<br><br> * Call by Reference – Value passed will get modified in both inside and outside the functions and it returns the same or different value. <br>
</details>

<details>
<summary>What is super keyword ?</summary>
<br>
The super keyword is used to invoke the overridden method, which overrides one of its superclass methods. This keyword allows to access overridden methods and also to access hidden members of the superclass.<br>It also forwards a call from a constructor, to a constructor in the superclass.<br>
</details>

<details>
<summary>What is method overriding ?</summary>
<br>
Method overriding is a feature that allows a subclass to provide the implementation of a method that overrides in the main class. It will override the implementation in the superclass by providing the same method name, same parameter, and same return type.
</details>

<details>
<summary>What is interface ?</summary>
<br>
An interface is a collection of an abstract method. If the class implements an interface, it thereby inherits all the abstract methods of an interface.<br>Java uses Interface to implement multiple inheritances.
</details>

<details>
<summary>Difference between overloading and overriding .</summary>
<br>
Overloading is static Binding, whereas Overriding is dynamic Binding. Overloading is nothing but the same method with different arguments, and it may or may not return the equal value in the same class itself.<br><br>Overriding is the same method names with the same arguments and return types associated with the class and its child class.<br>
</details>

<details>
<summary>What is abstraction ?</summary>
<br>
Abstraction is a useful feature of OOPS, and it shows only the necessary details to the client of an object. Meaning, it shows only required details for an object, not the inner constructors, of an object. Example – When you want to switch on the television, it is not necessary to know the inner circuitry/mechanism needed to switch on the TV. Whatever is required to switch on TV will be shown by using an abstract class.<br>
</details>

<details>
<summary>What are access modifiers ?</summary>
<br>
Access modifiers determine the scope of the method or variables that can be accessed from other various objects or classes. There are five types of access modifiers, and they are as follows: <br><br>-  Private<br>-   Protected<br>-   Public<br>-   Friend<br>- Protected Friend<br>
</details>

<details>
<summary>What is 'This' pointer ?</summary>
<br>
THIS pointer refers to the current object of a class. THIS keyword is used as a pointer which differentiates between the current object with the global object. It refers to the current object.
</details>

<details>
<summary>What is dynamic or run polymorphism ?</summary>
<br>
Dynamic or Run time polymorphism is also known as method overriding in which call to an overridden function is resolved during run time, not at the compile time. It means having two or more methods with the same name, same signature but with different implementation.
</details>

<details>
<summary>What is base class, sub class and super class ?</summary>
<br>
The base class is the most generalized class, and it is said to be a root class.<br>A Subclass is a class that inherits from one or more base classes.<br>The superclass is the parent class from which another class inherits.<br>
</details>

<details>
<summary>What is static and dynamic binding ?</summary>
<br>
Binding is nothing but the association of a name with the class. Static Binding is a binding in which name can be associated with the class during compilation time, and it is also called as early Binding. <br><br>Dynamic Binding is a binding in which name can be associated with the class during execution time, and it is also called as Late Binding.<br>
</details>









