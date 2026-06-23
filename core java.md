\-> new keyword - NEW Keyword Sends request to the class, \& class creates Object. Once the Object is created, NEW keyword will get Object’s address in a reference variable.



\-> garbage collector-Garbage Collector on regular basis keeps removing unused objects from RAM, thus avoiding overflow of memory, this helps us manage memory efficiently.



\-> non-static/instance variable->

&#x09;- created inside class but outside method without using “static” keyword.

&#x09;- Without creating object this variable cannot be accessed



\-> static variable-  created inside the class \& outside method using “static” keyword,

these variables belong to class and can be accessed with class name.



\-> methods

&#x09;- static or non-static



\-> variables

&#x09;- local

&#x09;- static

&#x09;- non-static

&#x09;- reference



\-> stack and heap memory



\-> data types

* byte
* short
* int
* long
* float
* double
* char
* Boolean
* String
* var-dynamic



\-> conventions in java

* all keywords -> lowercase - new,class,static,int,short
* class name -> uppercase,camelcasing
* variable name ->

&#x09;- special character-> "\_" and "$" use anywhere



\-> methods

* void
* return value
* return





\-> constructors: special method - used to initialize the object

* same name as that of Class
* permanently void
* cannot be->abstract, static, final
* cannot return->any value



constructor overloading

* more than one constructor in same class provided they are different no. of arguments \& different type of arguments.



\-> this keyword

There are two usages of “this” keyword:

• this.memberName; (The member here is a non static member).

• this(); (It is used to call constructor but this call should happen from another constructor.



\-> constructor chaining

* &#x20;When we call one constructor from another constructor is called as constructor chaining.
* While calling constructor from another constructor “this()” keyword should always be First statement.



\->OOPs

* inheritance
* polymorphism
* encapsulation
* abstraction



\-> unary operator



\-> packages

* package name cannot be a keyword
* it should be in lowercase



\-> access specifiers/modifiers

* private
* default
* protected
* public



\->IIB and SIB



\-> Polymorphism

i. Overriding

ii. Overloading



\-> Encapsulation

* private - variable
* public - getters \& setters



\-> Interface

&#x09;Class	  -	extends		->	Class

&#x09;Interface -	extends		->	Interface

&#x09;Class	  -	implements	->	Interface



* achieve by using the interface

&#x09;- abstraction

&#x09;- multiple inheritance

&#x09;- loose coupling



\-> final keyword

* variable	- value once initialized then cannot be changed
* static/non-static variable-initialization is mandatory
* variable - in UpperCase
* class- inheritance is not allowed
* method - overriding is not allowed









\-> casting - upcasting 	- child class object's address into parent class reference variable

&#x09;   - downcasting - parent class object's address into child class reference variable





Before Java -8

\---------------

\-> Interface

* every variable by default final and static
* reference variable - can be created
* object- cannot be created





**-> Java 8 new features**

**=========================**

* functional interface
* lambda expression
* default keyword
* stream api
* optional class



\-> Functional Interface - can consist of exactly one incomplete method in it

* Annotation - @FunctionalInterface



\-> Lambda Expression

* only be applicable on functional interface



Interface

\-----------

\-> default keyword

* java version -8
* we can create complete methods inside an interface
* functional interface-> consist one incomplete method, but can have any number of complete methods.



* add main method in interface
* develop complete static methods





Abstraciton

=============

abstraction achieved -> using interface and abstract class



in interface

\--------------

* abstract keyword - helps us to define incomplete methods



in class

\---------

* abstract class

\----------------

* can have static and non-static variables
* An abstract class can have multiple constructors
* incomplete methods
* complete methods -(concrete methods)
* main method
* object can't be created directly
* static, final and nested classes/methods



An abstract class can be 0% to 100% incomplete.

\------------------------------------------------

* 0% incomplete (100% complete methods) → No abstract methods, but class is still declared abstract.
* Partially incomplete → Contains both abstract and concrete methods.
* 100% incomplete → All methods are abstract.





super keyword

\--------------

* Access parent variables → super.variable
* Access parent methods → super.method()
* Call parent constructor → super()
* super() is automatically added by the compiler.
* super() must be the first statement in a constructor.
* Can access static and non-static parent members.
* Cannot be used inside static methods.
* Refers to the immediate parent class only.
* this and super can't be used in same method
* doesn't support multiple inheritance





Exception

\-----------

Whenever a bad user input is given, it will halt the program execution abruptly. This is called

as “exception”.



try{



}catch(){



}



“printStackTrace()":- To know the exact line number where exception has occurred





types-> Runtime and Compile Time/checked exception

* CompileTime/Checked Exception	-> .java to .class
* Runtime/Unchecked Exception		-> run .class file





\-> Loops

\--------

* for
* while
* do-while



break- terminate loop and switch

\-----



\-> continue -

\------------



\-> Conditional Statements

\--------------------------

* if else
* else if
* switch



\-> Scanner class

\---------------------



\-> Arrays

\---------



\-> File Handling

\--------------------



\-> Serialization and De-Serialization

\-----------------------------------------

* transient keyword





\-> marker interface

\-----------------------



\-> ObjectClass- the super most class in java

