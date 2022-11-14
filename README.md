# Self Written Core Java Notes<br>

[<b>Chapter 1 : Introduction to Language Fundamentals</b><br>](#chap1)
[<b>Chapter 2 : Opreators and Assignments</b><br>](#chap2)
[<b>Chapter 3 : Flow Control</b><br>](#chap3)
[<b>Chapter 4 : Declaration & Access Modifiers</b><br>](#chap4)
[<b>Chapter 5 : OOPs Concepts</b><br>](#chap5)
[<b>Chapter 6 : Exception Handling</b><br>](#chap6)
[<b>Chapter 7 : Collection</b><br>](#chap7)
[<b>Chapter 8 : java.lang Package</b><br>](#chap8)
[<b>Chapter 9 : Multithreading</b><br>](#chap9)
[<b>Chapter 10 : Multithreading Enhancement</b><br>](#chap10)
[<b>Chapter 11 : JVM Architecture</b><br>](#chap11)
[<b>Chapter 12 : Inner Classes</b><br>](#chap12)
[<b>Chapter 13 : File IO</b><br>](#chap13)
[<b>Chapter 14 : Serialization</b><br>](#chap14)
[<b>Chapter 15 : Generics</b><br>](#chap15)
[<b>Chapter 16 : Assertion</b><br>](#chap16)
[<b>Chapter 17 : Development</b><br>](#chap17)
[<b>Chapter 18 : Garbage Collection</b><br>](#chap18)
[<b>Chapter 19 : Enumeration</b><br>](#chap19)
[<b>Chapter 20 : Internationalization (I18N)</b><br>](#chap20)
[<b>Chapter 21 : Regular Expression</b><br>](#chap21)
[<b>Chapter 22 : Concurrent Collections</b><br>](#chap22)

# Contents <br>

<pre id="chap1"><b>Chapter 1 : Introduction to Language Fundamentals</b><br></pre>
- Identifiers & Reserve Keywords<br>
- Data Types<br>
- Literals<br>
- Arrays<br>
- main() method<br>
- Command Line Arguments<br>
- Coding Standards<br>

<pre id="chap2"><b>Chapter 2 : Opreators and Assignments</b><br></pre>
  - Increment & Decrement Operator<br>
  - Arithmetic Operators<br>
  - String Concatenation Operator<br>
  - Relational Operators<br>
  - Equality Operators<br>
  - instanceOf Operator<br>
  - Bitwise Operators<br>
  - Short Circuit Operator<br>
  - Type Cast Operator<br>
  - Assignment Operator<br>
  - Conditional Operator<br>
  - new Operator<br>
  - [] Operator<br>
  - Operator Precedence<br>
  - Evaluation order of Operands<br>
  - new vs newInstance<br>
  - instanceof vs isInstance()<br>
  - ClassNotFoundException vs NoClassDefFoundError<br>
  
<pre id="chap3"><b>Chapter 3 : Flow Control</b><br></pre>
  - if-else Statement <br>
  - switch Statement <br>
  - while loop <br>
  - for loop <br>
  - for-each loop / Enhanced for loop <br>
  - break <br>
  - continue <br>

<pre id="chap4"><b>Chapter 4 : Declaration & Access Modifiers</b><br></pre>
  - Java source file structure <br>
  - Class Level Modifiers <br>
  - Member Level Modifiers <br>
  - Interfaces <br>

<pre id="chap5"><b>Chapter 5 : OOPs Concepts</b><br></pre>
  - Data Hiding <br>
  - Abstraction <br>
  - Excapsulation <br>
  - Tightly Excapsulation class<br>
  - IS-A Relationship<br>
  - Has-A Relationship<br>
  - Method Signature<br>
  - Overloading<br>
  - Overriding<br>
  - Static control flow<br>
  - Instance control flow<br>
  - Constructor<br>
  - Coupling<br>
  - Cohesion<br>
  - Type-Casting<br>
  - Singleton Class

<pre id="chap6"><b>Chapter 6 : Exception Handling</b><br></pre>
  - Introduction<br>
  - Runtime Stack Mechanism<br>
  - Default exception handling in java
  - Exception class hierarchy
  - Customized exception handling using try-catch
  - Control flow in try-catch
  - Methods to print exception information
  - try with mutiple catch blocks
  - finally block
  - Difference between final,finally,finalize
  - Control flow in try-catch-finally
  - Control flow in nested try-catch-finally
  - Various possible combinations of try-catch-finally
  - throw keyword
  - throws keyword
  - Exception handling keyword summary
  - Various possible compile-time errors in exception handling
  - Customized (or) User-defined exceptions
  - Top-10 exceptions
  - Java 1.7 Enhancements
    - try-with resources
    - multi-catch block
 

<pre id="chap7"><b>Chapter 7 : Collection</b><br></pre>
  - Limitations of Array
  - Differences : Array vs Collection
  - Collection & Collection Framework
  - 9 Key interfaces of Collection Framework
  - Collection(I)
  - List(I)
    - ArrayList
    - LinkedList
    - Vector
    - Stack
  - 3 Cursors of Java
    - Enumerarion
    - Iterator
    - ListIterator
  - Set(I)
    - HashSet
    - LinkedHashSet
    - SortedSet
    - TreeSet
  - Comparable
  - Comparator
  - Map(I)
    - HashMap
    - LinkedHashMap
    - IdentityHashMap
    - WeakHashMap
    - SortedMap
    - TreeMap
    - Hashtable
    - Properties
  - Queue(I)
    - PriorityQueue
  - NavigableSet
  - NavigableMap
  - Collections - Utility Class 1
  - Arrays - Utility Class 2
  
<pre id="chap8"><b>Chapter 8 : java.lang Package</b><br></pre>
  - Introduction to java.lang package
  - Object Class
  - String Class
  - StringBuffer Class
  - StringBuilder Class
  - Wrapper Class
  - Autoboxing & Autounboxing
  
<pre id="chap9"><b>Chapter 9 : Multithreading</b><br></pre>
  - Introduction to Multithreading
  - Ways to define a Thread
    - By extending Thread Class
    - By implementing Runnable Interface
  - Getting & Setting a name of Thread
  - Thread Priorities
  - Methods to prevent Thread execution
    - yield()
    - join()
    - sleep()
  - Synchronization
  - Inter-Thread Communication
  - Deadlock
  - Daemon Threads
    
<pre id="chap10"><b>Chapter 10 : Multithreading Enhancement</b><br></pre>
  - ThreadGroup Class
  - java.util.concurrent package
    - Lock (Interface)
    
<pre id="chap11"><b>Chapter 11 : JVM Architecture</b><br></pre>
  - Virtual Machine
  - Types of Virtual Machine
    - Hardware based VM
    - Application based VM
  - Basic Architecture of VM
  - Class Loader Subsystem
    - Loading
    - Linking
    - Initialization
  - Types of Classloaders
    - Bootstrap CL
    - Extension CL
    - Application CL
  - How classloaders work
  - Need of customized classloader
  - Psuedo code of customized classloader
  - Memory Aread of JVM
    - Method Area
    - Heap Area
    - Stack Area
    - PC registers
    - Native method stacks
  - Program to display head memory stats
  - How to set Min & Max head size
  - Execution Engine
    - Interpreter
    - JIT Compiler
  - Java Native Interface (JNI)
  - Complete Architecture Diagram of JVM
  - Class file structure
  
<pre id="chap12"><b>Chapter 12 : Inner Classes</b><br></pre>
  - Introduction to Inner Class 
  - Normal/Regular Inner Class
  - Method Local Inner Class
  - Anonymous Inner Class
    - Normal Java Class vs Anonymous Inner Class
    - Where Anonymous Inner Class are best suitable
  - Static Nested Class
  
<pre id="chap13"><b>Chapter 13 : File IO</b><br></pre>
  - File
  - FileWriter
  - FileReader
  - BufferedWriter
  - BufferedReader
  - PrintWriter
  
<pre id="chap14"><b>Chapter 14 : Serialization</b><br></pre>
  - Introduction
  - Object Graph in Serialization
  - Customized Serialization
  - Serialization w.r.t Inheritance
  - Externalization
  - SerialversionUID
  
<pre id="chap15"><b>Chapter 15 : Generics</b><br></pre>
  - Introduction
  - Generic Classes
  - Bounded Types
  - Generics methods & Wild-card Character (?)
  - Communication with non-generic code
  - Conclusions
  
<pre id="chap16"><b>Chapter 16 : Assertion</b><br></pre>
  - Introduction of Assertion
  - "assert" as a keyword & identifier
  - Types of assert statement
  - Various possible runtime flags
  - Appropriate & Inappropriate use of assertions
  - AssertionError
  
<pre id="chap17"><b>Chapter 17 : Development</b><br></pre>
  - javac command
  - java command
  - classpath settings
  - JAR files
  - System Properties
  - JAR vs WAR vs EAR
  - Web Application vs Enterprise Application
  - Web Server vs Application Server
  - How to create executable JAR file?
  - Ways to run java program
  - classpath vs path
  - JDK vs JRE vs JVM
  - java vs javaw vs javaws
  
<pre id="chap18"><b>Chapter 18 : Garbage Collection</b><br></pre>
  - Introduction
  - Ways to make an object eligible to GC
  - Methods for requesting JVM to run GC
  - Finzalization
 
<pre id="chap19"><b>Chapter 19 : Enumeration</b><br></pre>
  - Introduction
  - Internal Implementation of enum
  - enum declaration & usage
  - enum vs switch
  - enum vs inheritance
  - java.lang.Enum
  - ordinal() method
  - Speciality of java enum
  - enum vs constructor
  - enum vs Enum vs Enumeration

<pre id="chap20"><b>Chapter 20 : Internationalization (I18N)</b><br></pre>
  - Introduction
  - Locale
  - NumberFormat
  - DateFormat
  
<pre id="chap21"><b>Chapter 21 : Regular Expression</b><br></pre>
  - Introduction
  - Pattern
  - Matcher
  - Character Classes
  - Predefined Character Classes
  - Quantifiers
  - Pattern class split() method
  - String Tokenizer
  
<pre id="chap22"><b>Chapter 22 : Concurrent Collections</b><br><br></pre>
  - ConcurrentHashMap
  - CopyOnWriteArrayList
  - CopyOnWriteArraySet

(Credits : Notes are prepared by watching Durga sir's videos from DurgaSoft)
