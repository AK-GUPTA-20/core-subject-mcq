# Java MCQ Questions for Company Preparation

A structured set of 165 Java multiple-choice questions in GitHub‑friendly Markdown format. This collection is designed for company interview preparation and covers core Java, OOP, JVM, collections, exception handling, multithreading, Java 8+, and coding‑style MCQs.


---

## 1. Java Basics

### Q1. Which of the following is true about Java?
A. Java is platform‑dependent  
B. Java supports only procedural programming  
C. Java is platform‑independent through bytecode  
D. Java does not support OOP  

**Answer:** C  
**Explanation:** Java source code is compiled into bytecode, which runs on the JVM across platforms.

### Q2. Which component converts Java source code into bytecode?
A. JVM  
B. JDK  
C. JRE  
D. javac  

**Answer:** D  
**Explanation:** `javac` is the Java compiler that converts `.java` files into `.class` bytecode files.

### Q3. Which of the following is not a Java keyword?
A. static  
B. Boolean  
C. final  
D. try  

**Answer:** B  
**Explanation:** `Boolean` is a wrapper class, not a Java keyword.

### Q4. What is the default value of an `int` instance variable in Java?
A. 0  
B. null  
C. undefined  
D. 1  

**Answer:** A  
**Explanation:** Numeric instance variables get default values; `int` defaults to 0.

### Q5. Which method is the entry point of a Java program?
A. start()  
B. run()  
C. main()  
D. init()  

**Answer:** C  
**Explanation:** Execution begins from `public static void main(String[] args)`.

### Q6. Which of the following is used to create an object in Java?
A. class  
B. object  
C. new  
D. create  

**Answer:** C  
**Explanation:** The `new` keyword allocates memory and creates an object.

### Q7. Which primitive data type stores a single character?
A. String  
B. char  
C. character  
D. byte  

**Answer:** B  
**Explanation:** `char` stores a single 16‑bit Unicode character.

### Q8. Size of `double` in Java is:
A. 2 bytes  
B. 4 bytes  
C. 8 bytes  
D. 16 bytes  

**Answer:** C  
**Explanation:** `double` is a 64‑bit floating‑point type.

### Q9. Which symbol is used to inherit a class in Java?
A. implements  
B. inherits  
C. extends  
D. super  

**Answer:** C  
**Explanation:** A class inherits another class using `extends`.

### Q10. Which package is imported by default in every Java program?
A. java.util  
B. java.lang  
C. java.io  
D. java.net  

**Answer:** B  
**Explanation:** `java.lang` is automatically imported.

### Q11. Which operator is used for comparison of values?
A. =  
B. ==  
C. equals  
D. :=  

**Answer:** B  
**Explanation:** `==` compares primitive values directly.

### Q12. Which of the following is not a primitive type?
A. float  
B. boolean  
C. String  
D. char  

**Answer:** C  
**Explanation:** `String` is a class, not a primitive type.

### Q13. Which loop is guaranteed to execute at least once?
A. for  
B. while  
C. do‑while  
D. enhanced for  

**Answer:** C  
**Explanation:** `do‑while` checks the condition after executing the body once.

### Q14. Which statement is used to exit a loop immediately?
A. skip  
B. continue  
C. break  
D. exit  

**Answer:** C  
**Explanation:** `break` terminates the nearest loop or switch.

### Q15. Which statement skips the current iteration of a loop?
A. break  
B. continue  
C. return  
D. pass  

**Answer:** B  
**Explanation:** `continue` moves control to the next iteration.

### Q16. What is the default value of a `boolean` instance variable?
A. true  
B. false  
C. null  
D. 0  

**Answer:** B  
**Explanation:** The default value of `boolean` instance fields is `false`.

### Q17. Which one is a valid identifier in Java?
A. 1value  
B. class  
C. _count  
D. total‑value  

**Answer:** C  
**Explanation:** Identifiers cannot start with digits, contain hyphens, or use reserved keywords.

### Q18. Which keyword prevents a variable from being modified?
A. static  
B. final  
C. const  
D. fixed  

**Answer:** B  
**Explanation:** `final` makes a variable constant after initialization.

### Q19. Which conversion happens automatically?
A. double to int  
B. long to short  
C. int to long  
D. float to byte  

**Answer:** C  
**Explanation:** Widening conversions like `int` to `long` happen implicitly.

### Q20. Which tool is used to run Java bytecode?
A. javac  
B. java  
C. javadoc  
D. jar  

**Answer:** B  
**Explanation:** The `java` command launches the JVM to run bytecode.

---

## 2. OOP Concepts

### Q21. Which OOP concept allows one interface to be used for different underlying forms?
A. Encapsulation  
B. Polymorphism  
C. Inheritance  
D. Abstraction  

**Answer:** B  
**Explanation:** Polymorphism allows the same method name or interface to behave differently.

### Q22. Wrapping data and methods together in one unit is called:
A. Inheritance  
B. Abstraction  
C. Encapsulation  
D. Overloading  

**Answer:** C  
**Explanation:** Encapsulation binds state and behavior into a class.

### Q23. Which OOP concept hides implementation details?
A. Abstraction  
B. Inheritance  
C. Composition  
D. Binding  

**Answer:** A  
**Explanation:** Abstraction exposes only essential features.

### Q24. Method overloading is resolved at:
A. Runtime  
B. Compile time  
C. Load time  
D. Execution end  

**Answer:** B  
**Explanation:** The compiler determines overloaded methods based on parameters.

### Q25. Method overriding is resolved at:
A. Compile time  
B. Runtime  
C. Parse time  
D. Preprocessing time  

**Answer:** B  
**Explanation:** Overriding uses dynamic method dispatch at runtime.

### Q26. Can a constructor be inherited?
A. Yes  
B. No  
C. Only private constructors  
D. Only protected constructors  

**Answer:** B  
**Explanation:** Constructors are not inherited by subclasses.

### Q27. Which keyword refers to the current object?
A. super  
B. self  
C. this  
D. current  

**Answer:** C  
**Explanation:** `this` points to the current object instance.

### Q28. Which keyword refers to the parent class object?
A. parent  
B. base  
C. this  
D. super  

**Answer:** D  
**Explanation:** `super` is used to access parent class members.

### Q29. Which of these supports runtime polymorphism?
A. Method overriding  
B. Method overloading  
C. Constructor overloading  
D. Static methods  

**Answer:** A  
**Explanation:** Overriding provides runtime polymorphism.

### Q30. Which keyword is used to prevent inheritance?
A. private  
B. final  
C. static  
D. constant  

**Answer:** B  
**Explanation:** A `final` class cannot be extended.

### Q31. Java supports multiple inheritance through:
A. Classes  
B. Interfaces  
C. Constructors  
D. Packages  

**Answer:** B  
**Explanation:** A class can implement multiple interfaces.

### Q32. Which access modifier makes a member accessible only within the same class?
A. public  
B. protected  
C. default  
D. private  

**Answer:** D  
**Explanation:** `private` members are visible only inside the same class.

### Q33. Which access modifier allows access within the package and subclasses outside the package?
A. private  
B. protected  
C. public  
D. default  

**Answer:** B  
**Explanation:** `protected` gives package access plus subclass access outside the package.

### Q34. Which is not an OOP pillar?
A. Encapsulation  
B. Abstraction  
C. Compilation  
D. Polymorphism  

**Answer:** C  
**Explanation:** Compilation is a language process, not an OOP pillar.

### Q35. What happens if a subclass constructor does not explicitly call `super()`?
A. Compilation error always  
B. Java inserts `super()` automatically if possible  
C. Parent constructor is never called  
D. Object is not created  

**Answer:** B  
**Explanation:** Java adds a no‑argument `super()` call implicitly when valid.

### Q36. Which method can never be overridden?
A. instance method  
B. abstract method  
C. final method  
D. public method  

**Answer:** C  
**Explanation:** `final` methods cannot be overridden.

### Q37. Which relationship represents “has‑a”?
A. Inheritance  
B. Composition  
C. Polymorphism  
D. Overriding  

**Answer:** B  
**Explanation:** Composition models a has‑a relationship.

### Q38. Which keyword is used to create an abstract class?
A. interface  
B. final  
C. virtual  
D. abstract  

**Answer:** D  
**Explanation:** `abstract` is used for abstract classes and methods.

### Q39. An abstract class:
A. Can be instantiated directly  
B. Cannot contain constructors  
C. Can have both abstract and concrete methods  
D. Cannot have fields  

**Answer:** C  
**Explanation:** Abstract classes can contain both implemented and unimplemented methods.

### Q40. Which member belongs to the class rather than objects?
A. local variable  
B. instance variable  
C. static member  
D. constructor  

**Answer:** C  
**Explanation:** Static members are shared at the class level.

---

## 3. Strings and Arrays

### Q41. Strings in Java are:
A. Mutable  
B. Immutable  
C. Primitive  
D. Stored only in heap without pooling  

**Answer:** B  
**Explanation:** `String` objects are immutable in Java.

### Q42. Which class is mutable?
A. String  
B. StringBuilder  
C. Integer  
D. Character  

**Answer:** B  
**Explanation:** `StringBuilder` allows modifying character sequences.

### Q43. Which method compares string contents?
A. ==  
B. compare  
C. equals()  
D. content()  

**Answer:** C  
**Explanation:** `equals()` compares actual string contents.

### Q44. What does `==` compare for objects?
A. Content  
B. References  
C. Length  
D. Hash codes  

**Answer:** B  
**Explanation:** `==` checks whether two references point to the same object.

### Q45. Which class is faster for string concatenation in a single thread?
A. String  
B. StringBuilder  
C. StringBuffer  
D. Character  

**Answer:** B  
**Explanation:** `StringBuilder` is unsynchronized and faster in single‑threaded use.

### Q46. Which class is thread‑safe among these?
A. StringBuilder  
B. StringJoiner  
C. StringBuffer  
D. String  

**Answer:** C  
**Explanation:** `StringBuffer` methods are synchronized.

### Q47. Arrays in Java are:
A. Dynamically resizable  
B. Fixed in size after creation  
C. Primitive only  
D. Not objects  

**Answer:** B  
**Explanation:** Array size is fixed when the array is created.

### Q48. Array indexing starts from:
A. 1  
B. -1  
C. 0  
D. Depends on compiler  

**Answer:** C  
**Explanation:** Java arrays are zero‑indexed.

### Q49. Which exception occurs for invalid array index access?
A. NullPointerException  
B. ArrayStoreException  
C. ArithmeticException  
D. ArrayIndexOutOfBoundsException  

**Answer:** D  
**Explanation:** Accessing an invalid index throws `ArrayIndexOutOfBoundsException`.

### Q50. Which method gives the length of an array?
A. length()  
B. size()  
C. length  
D. getLength()  

**Answer:** C  
**Explanation:** Arrays use the `length` field, not a method.

### Q51. Which method gives the length of a String?
A. length  
B. size()  
C. count()  
D. length()  

**Answer:** D  
**Explanation:** Strings use the `length()` method.

### Q52. Which method converts a string to lowercase?
A. lower()  
B. toLowerCase()  
C. lowerCase()  
D. convertLower()  

**Answer:** B  
**Explanation:** `toLowerCase()` converts all characters to lowercase.

### Q53. Which method removes leading and trailing spaces?
A. trim()  
B. stripAll()  
C. remove()  
D. clean()  

**Answer:** A  
**Explanation:** `trim()` removes leading and trailing whitespace.

### Q54. Which utility class provides array helper methods like sorting?
A. ArrayHelper  
B. Collections  
C. Arrays  
D. Utility  

**Answer:** C  
**Explanation:** `java.util.Arrays` contains methods like `sort()` and `binarySearch()`.

### Q55. Which method is used to split a string?
A. divide()  
B. split()  
C. break()  
D. tokenize()  

**Answer:** B  
**Explanation:** `split()` divides a string based on a regex delimiter.

---

## 4. Exception Handling

### Q56. Which keyword is used to handle exceptions?
A. catch  
B. throw  
C. throws  
D. final  

**Answer:** A  
**Explanation:** `catch` handles exceptions thrown in the `try` block.

### Q57. Which block always executes except in rare JVM termination cases?
A. try  
B. catch  
C. finally  
D. throws  

**Answer:** C  
**Explanation:** `finally` is used for cleanup code.

### Q58. Which keyword is used to explicitly throw an exception?
A. throws  
B. catch  
C. throw  
D. final  

**Answer:** C  
**Explanation:** `throw` is used to manually throw an exception object.

### Q59. Which keyword declares exceptions in a method signature?
A. throw  
B. throws  
C. catch  
D. final  

**Answer:** B  
**Explanation:** `throws` specifies possible exceptions a method can propagate.

### Q60. Which of the following is an unchecked exception?
A. IOException  
B. SQLException  
C. ClassNotFoundException  
D. NullPointerException  

**Answer:** D  
**Explanation:** `NullPointerException` is a runtime exception.

### Q61. Which of the following is a checked exception?
A. ArithmeticException  
B. NullPointerException  
C. IOException  
D. ArrayIndexOutOfBoundsException  

**Answer:** C  
**Explanation:** Checked exceptions must be handled or declared.

### Q62. What is the parent class of all exceptions and errors?
A. Exception  
B. Error  
C. Throwable  
D. Object  

**Answer:** C  
**Explanation:** `Throwable` is the root class for exception handling.

### Q63. Which exception occurs when dividing by zero with integers?
A. NumberFormatException  
B. ArithmeticException  
C. IOException  
D. IllegalArgumentException  

**Answer:** B  
**Explanation:** Integer division by zero throws `ArithmeticException`.

### Q64. Which exception occurs when accessing a method on a null reference?
A. IOException  
B. ArithmeticException  
C. NullPointerException  
D. SQLException  

**Answer:** C  
**Explanation:** Dereferencing `null` causes `NullPointerException`.

### Q65. Can there be multiple catch blocks for one try block?
A. No  
B. Yes  
C. Only two  
D. Only one if finally exists  

**Answer:** B  
**Explanation:** A single `try` can have multiple `catch` blocks.

### Q66. What happens if an exception is not handled?
A. Program always ignores it  
B. It is automatically converted to warning  
C. It propagates up the call stack  
D. JVM restarts  

**Answer:** C  
**Explanation:** Unhandled exceptions move up the call stack until handled or program ends.

### Q67. Which block cannot exist without a try block?
A. finally  
B. if  
C. switch  
D. for  

**Answer:** A  
**Explanation:** `finally` must be attached to a `try` block.

### Q68. `NumberFormatException` is thrown when:
A. Dividing by zero  
B. Parsing invalid numeric string  
C. Accessing null object  
D. Opening missing file  

**Answer:** B  
**Explanation:** It occurs when converting an invalid string to a number.

### Q69. Which is better for specific handling order in catch blocks?
A. General to specific  
B. Specific to general  
C. Random order  
D. Alphabetical order  

**Answer:** B  
**Explanation:** More specific exceptions should be caught before general ones.

### Q70. Which statement about `finally` is correct?
A. It runs only when exception occurs  
B. It runs only when no exception occurs  
C. It is generally used for resource cleanup  
D. It replaces `catch`  

**Answer:** C  
**Explanation:** `finally` commonly closes resources or releases locks.

---

## 5. Collections Framework

### Q71. Which interface represents an ordered collection that allows duplicates?
A. Set  
B. Map  
C. List  
D. Queue  

**Answer:** C  
**Explanation:** `List` maintains insertion order and allows duplicates.

### Q72. Which collection does not allow duplicates?
A. ArrayList  
B. LinkedList  
C. HashSet  
D. Vector  

**Answer:** C  
**Explanation:** `Set` implementations like `HashSet` do not allow duplicate elements.

### Q73. Which collection stores key‑value pairs?
A. Set  
B. Map  
C. List  
D. Queue  

**Answer:** B  
**Explanation:** `Map` stores entries as key‑value pairs


### Q74. Which implementation is best for frequent random access?
A. ArrayList  
B. LinkedList  
C. PriorityQueue  
D. TreeSet  

**Answer:** B  
**Explanation:** `ArrayList` provides fast index‑based access.

### Q75. Which implementation is better for frequent insertion/deletion in middle positions?
A. ArrayList  
B. LinkedList  
C. HashMap  
D. HashSet  

**Answer:** B  
**Explanation:** `LinkedList` handles insertions/removals more efficiently in linked structure terms.

### Q76. Which map does not maintain any order?
A. TreeMap  
B. LinkedHashMap  
C. HashMap  
D. ConcurrentHashMap  

**Answer:** C  
**Explanation:** `HashMap` does not guarantee iteration order.

### Q77. Which map maintains insertion order?
A. TreeMap  
B. LinkedHashMap  
C. HashMap  
D. Hashtable  

**Answer:** B  
**Explanation:** `LinkedHashMap` preserves insertion order.

### Q78. Which map sorts keys in natural order?
A. HashMap  
B. LinkedHashMap  
C. TreeMap  
D. IdentityHashMap  

**Answer:** C  
**Explanation:** `TreeMap` stores keys in sorted order.

### Q79. Which collection is synchronized by default among these?
A. ArrayList  
B. HashMap  
C. Vector  
D. HashSet  

**Answer:** C  
**Explanation:** `Vector` methods are synchronized.

### Q80. Which class allows one null key in standard implementation?
A. Hashtable  
B. TreeMap always  
C. HashMap  
D. ConcurrentHashMap  

**Answer:** C  
**Explanation:** `HashMap` allows one null key and multiple null values.

### Q81. Which map does not allow null key or null value?
A. HashMap  
B. LinkedHashMap  
C. Hashtable  
D. WeakHashMap  

**Answer:** C  
**Explanation:** `Hashtable` does not permit null keys or values.

### Q82. Which interface is implemented by `HashSet` internally using a map?
A. List  
B. Queue  
C. Set  
D. Deque  

**Answer:** C  
**Explanation:** `HashSet` implements `Set` and internally uses a `HashMap`.

### Q83. Which method is used to add an element to a `List`?
A. put()  
B. add()  
C. insert()  
D. append()  

**Answer:** B  
**Explanation:** `add()` inserts elements into a list.

### Q84. Which method removes a key‑value mapping from a `Map`?
A. delete()  
B. clearKey()  
C. remove()  
D. erase()  

**Answer:** C  
**Explanation:** `remove()` deletes an entry by key.

### Q85. Which traversal interface is modern and commonly used for collections?
A. Enumeration  
B. Iterator  
C. Scanner  
D. Reader  

**Answer:** B  
**Explanation:** `Iterator` is widely used to traverse collections.

### Q86. Which iterator allows bidirectional traversal?
A. Iterator  
B. Enumeration  
C. ListIterator  
D. Spliterator only backward  

**Answer:** C  
**Explanation:** `ListIterator` can move forward and backward.

### Q87. Which collection allows duplicate elements and maintains sorted order?
A. TreeSet  
B. PriorityQueue  
C. ArrayList  
D. LinkedHashSet  

**Answer:** B  
**Explanation:** `PriorityQueue` allows duplicates and orders elements by priority.

### Q88. Which operation is generally O(1) on average in `HashMap`?
A. Search by key  
B. Sorting all keys  
C. Traversing all entries  
D. Rehashing  

**Answer:** A  
**Explanation:** Hash‑based lookup is average O(1).

### Q89. Which collection is best to represent unique sorted elements?
A. ArrayList  
B. HashSet  
C. TreeSet  
D. Vector  

**Answer:** C  
**Explanation:** `TreeSet` stores unique elements in sorted order.

### Q90. Which class is legacy synchronized map implementation?
A. HashMap  
B. TreeMap  
C. Hashtable  
D. LinkedHashMap  

**Answer:** C  
**Explanation:** `Hashtable` is the legacy synchronized map.

---

## 6. Multithreading and Concurrency

### Q91. Which method starts a new thread?
A. run()  
B. execute()  
C. start()  
D. init()  

**Answer:** C  
**Explanation:** `start()` creates a new call stack and invokes `run()`.

### Q92. Which method contains the code executed by a thread?
A. main()  
B. run()  
C. start()  
D. call()  

**Answer:** B  
**Explanation:** Thread logic is written inside `run()`.

### Q93. Which keyword ensures visibility of changes across threads?
A. final  
B. static  
C. volatile  
D. native  

**Answer:** C  
**Explanation:** `volatile` ensures visibility of variable updates across threads.

### Q94. Which keyword is used for intrinsic locking?
A. synchronized  
B. locked  
C. atomic  
D. threadsafe  

**Answer:** A  
**Explanation:** `synchronized` provides monitor‑based locking.

### Q95. Which method causes the current thread to pause for some time?
A. wait()  
B. join()  
C. sleep()  
D. stop()  

**Answer:** C  
**Explanation:** `Thread.sleep()` pauses the current thread for a duration.

### Q96. Which method waits for another thread to complete?
A. sleep()  
B. wait()  
C. join()  
D. notify()  

**Answer:** C  
**Explanation:** `join()` blocks until the target thread finishes.

### Q97. Which method releases the monitor and waits?
A. sleep()  
B. yield()  
C. wait()  
D. suspend()  

**Answer:** C  
**Explanation:** `wait()` must be called inside synchronized context and releases the lock.

### Q98. Which method wakes up one waiting thread?
A. start()  
B. resume()  
C. notify()  
D. join()  

**Answer:** C  
**Explanation:** `notify()` wakes one thread waiting on the object's monitor.

### Q99. Which method wakes all waiting threads?
A. signal()  
B. notifyAll()  
C. wakeAll()  
D. resumeAll()  

**Answer:** B  
**Explanation:** `notifyAll()` wakes all waiting threads on that monitor.

### Q100. Which interface can be implemented to create a thread task?
A. Executable  
B. Action  
C. Runnable  
D. Serializable  

**Answer:** C  
**Explanation:** `Runnable` is a common way to define thread tasks.

### Q101. Which interface returns a result and can throw checked exceptions?
A. Runnable  
B. Callable  
C. Comparable  
D. Supplier only  

**Answer:** B  
**Explanation:** `Callable` returns a value and may throw checked exceptions.

### Q102. Which utility manages a pool of threads?
A. ThreadGroup  
B. ExecutorService  
C. Runtime  
D. Timer only  

**Answer:** B  
**Explanation:** `ExecutorService` manages thread execution efficiently.

### Q103. Which state means a thread is eligible to run?
A. Blocked  
B. Waiting  
C. Runnable  
D. Timed Waiting  

**Answer:** C  
**Explanation:** `Runnable` means ready or running depending on scheduler.

### Q104. Which issue occurs when two threads access shared data without proper synchronization?
A. Serialization  
B. Race condition  
C. Overloading  
D. Compilation error  

**Answer:** B  
**Explanation:** Race conditions cause inconsistent results due to uncontrolled interleaving.

### Q105. Which class provides atomic operations for integers?
A. Integer  
B. AtomicInteger  
C. MutableInt  
D. SyncInteger  

**Answer:** B  
**Explanation:** `AtomicInteger` supports lock‑free atomic updates.

### Q106. Which collection is thread‑safe for high concurrency reads/writes?
A. HashMap  
B. TreeMap  
C. ConcurrentHashMap  
D. LinkedHashMap  

**Answer:** C  
**Explanation:** `ConcurrentHashMap` is designed for concurrent access.

### Q107. Which thread method is deprecated due to unsafe behavior?
A. run()  
B. start()  
C. stop()  
D. join()  

**Answer:** C  
**Explanation:** `stop()` is deprecated because it can leave shared data inconsistent.

### Q108. Which method hints the scheduler to give chance to another thread?
A. sleep()  
B. yield()  
C. notify()  
D. join()  

**Answer:** B  
**Explanation:** `yield()` is a scheduling hint, not a guarantee.

### Q109. Daemon threads are:
A. User‑created only and immortal  
B. Background service threads  
C. Always high‑priority threads  
D. Threads that cannot be stopped  

**Answer:** B  
**Explanation:** Daemon threads run background tasks and stop when user threads finish.

### Q110. Which block is commonly used to protect critical section code?
A. synchronized block  
B. package block  
C. final block  
D. native block  

**Answer:** A  
**Explanation:** Critical sections are commonly guarded with `synchronized`.

---

## 7. JVM, Memory, and Advanced Core Java

### Q111. JVM stands for:
A. Java Variable Machine  
B. Java Virtual Machine  
C. Joint Virtual Manager  
D. Java Verified Machine  

**Answer:** B  
**Explanation:** JVM executes Java bytecode.

### Q112. JRE contains:
A. JVM + libraries to run Java applications  
B. Compiler only  
C. Source files only  
D. Database connector only  

**Answer:** A  
**Explanation:** JRE includes JVM and runtime libraries.

### Q113. JDK contains:
A. JRE + development tools  
B. JVM only  
C. Compiler only  
D. Bytecode only  

**Answer:** A  
**Explanation:** JDK includes JRE plus tools like `javac`.

### Q114. Which memory area stores objects?
A. Stack  
B. Heap  
C. Register  
D. CPU cache only  

**Answer:** B  
**Explanation:** Objects are generally allocated in heap memory.

### Q115. Which memory area stores local variables and method calls?
A. Heap  
B. Stack  
C. Method area only  
D. Eden space only  

**Answer:** B  
**Explanation:** Local variables and call frames are stored on the stack.

### Q116. Garbage collection in Java is used for:
A. Sorting memory  
B. Removing syntax errors  
C. Automatic memory reclamation  
D. Increasing CPU clock speed  

**Answer:** C  
**Explanation:** GC reclaims memory from unreachable objects.

### Q117. Which method is called before an object is garbage collected, though deprecated and unreliable?
A. dispose()  
B. close()  
C. finalize()  
D. delete()  

**Answer:** C  
**Explanation:** `finalize()` is deprecated and not recommended.

### Q118. Which keyword can be used to reference package‑level namespace?
A. import  
B. include  
C. using  
D. package  

**Answer:** D  
**Explanation:** `package` declares a namespace for classes.

### Q119. Which keyword prevents method from being inherited through overriding changes?
A. const  
B. final  
C. static  
D. native  

**Answer:** B  
**Explanation:** `final` on a method stops overriding.

### Q120. Which keyword indicates a method belongs to class and can be called without object?
A. public  
B. final  
C. static  
D. native  

**Answer:** C  
**Explanation:** Static methods belong to the class itself.

### Q121. Which class is superclass of all classes in Java?
A. Class  
B. Base  
C. Object  
D. Main  

**Answer:** C  
**Explanation:** All Java classes implicitly extend `Object`.

### Q122. Which method is commonly overridden to print object details meaningfully?
A. print()  
B. toString()  
C. display()  
D. stringify()  

**Answer:** B  
**Explanation:** Overriding `toString()` provides a readable object representation.

### Q123. Which two methods should be consistent for objects used in hash‑based collections?
A. toString() and clone()  
B. wait() and notify()  
C. equals() and hashCode()  
D. run() and start()  

**Answer:** C  
**Explanation:** Equal objects must return the same hash code.

### Q124. Which interface marks a class capable of being cloned?
A. Cloneable  
B. Serializable  
C. Runnable  
D. Copyable  

**Answer:** A  
**Explanation:** `Cloneable` indicates cloning is supported.

### Q125. Which interface marks a class for object serialization?
A. Externalizable only  
B. Serializable  
C. Cloneable  
D. Streamable  

**Answer:** B  
**Explanation:** `Serializable` enables object serialization.

### Q126. Which keyword is used for inheritance from an interface to a class?
A. extends  
B. inherits  
C. implements  
D. instanceOf  

**Answer:** C  
**Explanation:** Classes use `implements` to adopt interface behavior.

### Q127. Which operator checks object type at runtime?
A. typeof  
B. instanceof  
C. is  
D. ==  

**Answer:** B  
**Explanation:** `instanceof` checks whether an object belongs to a type.

### Q128. Which feature allows creating one class/method to work with different data types?
A. Serialization  
B. Reflection  
C. Generics  
D. Annotation  

**Answer:** C  
**Explanation:** Generics provide type safety and reusability.

### Q129. Type erasure is associated with:
A. Exceptions  
B. Generics  
C. Arrays  
D. Threads  

**Answer:** B  
**Explanation:** Generic type information is mostly removed at runtime.

### Q130. Which annotation indicates overriding a superclass method?
A. @Deprecated  
B. @SafeVarargs  
C. @Override  
D. @FunctionalInterface  

**Answer:** C  
**Explanation:** `@Override` tells the compiler the method should override a parent method.

---

## 8. Java 8+ and Interview‑Oriented MCQs

### Q131. Which feature was introduced in Java 8?
A. Packages  
B. Lambda expressions  
C. Bytecode  
D. Classes  

**Answer:** B  
**Explanation:** Java 8 introduced lambda expressions and streams.

### Q132. Which interface has exactly one abstract method?
A. Marker interface  
B. Functional interface  
C. Normal interface  
D. Abstract class  

**Answer:** B  
**Explanation:** Functional interfaces are used with lambdas.

### Q133. Which annotation is used with functional interfaces?
A. @Override  
B. @FunctionalInterface  
C. @Deprecated  
D. @Inherited  

**Answer:** B  
**Explanation:** It indicates the interface is intended to have one abstract method.

### Q134. Stream API is mainly used for:
A. File compression only  
B. Network communication only  
C. Processing collections in a declarative way  
D. Creating threads only  

**Answer:** C  
**Explanation:** Streams support filtering, mapping, reducing, and more.

### Q135. Which stream operation is intermediate?
A. collect()  
B. forEach()  
C. count()  
D. filter()  

**Answer:** D  
**Explanation:** `filter()` returns another stream, so it is intermediate.

### Q136. Which stream operation is terminal?
A. map()  
B. filter()  
C. sorted()  
D. collect()  

**Answer:** D  
**Explanation:** `collect()` produces the final result.

### Q137. Which optional container helps avoid null‑related issues?
A. Maybe  
B. Nullable  
C. Optional  
D. SafeValue  

**Answer:** C  
**Explanation:** `Optional` represents presence or absence of a value.

### Q138. Which method in Optional returns value if present, otherwise another value?
A. getOrDefault()  
B. orElse()  
C. default()  
D. ifNull()  

**Answer:** B  
**Explanation:** `orElse()` returns a fallback value.

### Q139. Which interface represents a function that accepts one argument and returns a result?
A. Consumer  
B. Supplier  
C. Predicate  
D. Function  

**Answer:** D  
**Explanation:** `Function<T, R>` transforms input into output.

### Q140. Which interface represents a boolean‑valued function?
A. Function  
B. Predicate  
C. Consumer  
D. Supplier  

**Answer:** B  
**Explanation:** `Predicate<T>` returns true or false.

### Q141. Which interface consumes a value and returns nothing?
A. Consumer  
B. Predicate  
C. Function  
D. Supplier  

**Answer:** A  
**Explanation:** `Consumer<T>` accepts input and has no return value.

### Q142. Which interface supplies a value without taking input?
A. Consumer  
B. Predicate  
C. Supplier  
D. Runnable  

**Answer:** C  
**Explanation:** `Supplier<T>` provides data without input arguments.

### Q143. Which method reference refers to a static method?
A. object::instanceMethod  
B. ClassName::staticMethod  
C. ClassName::new only  
D. this::super  

**Answer:** B  
**Explanation:** Static method references use `ClassName::methodName`.

### Q144. Which feature lets an interface define implemented methods?
A. native method  
B. default method  
C. abstract method  
D. private constructor  

**Answer:** B  
**Explanation:** Java 8 introduced default methods in interfaces.

### Q145. Which method is used to sort a list with custom logic in Java 8+?
A. Collections.arrange()  
B. Arrays.order()  
C. list.sort()  
D. queue.sort()  

**Answer:** C  
**Explanation:** `List.sort()` accepts a comparator for custom sorting.

### Q146. Which method is used to reverse the natural order of a comparator?
A. Comparator.reverseOrder()  
B. Comparator.naturalOrder()  
C. Comparator.defaultOrder()  
D. Comparator.basicOrder()  

**Answer:** A  
**Explanation:** `Comparator.reverseOrder()` returns a comparator that reverses natural ordering.

### Q147. Which class is used for date and time in Java 8 modern API?
A. Date only  
B. Calendar only  
C. LocalDate  
D. Timer  

**Answer:** C  
**Explanation:** `LocalDate` is part of the `java.time` API.


### Q148. Which statement about `var` in Java is true?
A. It can be used for fields  
B. It can be used for local variable type inference  
C. It replaces all generics  
D. It stores dynamic types  

**Answer:** B  
**Explanation:** `var` supports local variable type inference, not dynamic typing.

### Q149. Which switch enhancement is associated with newer Java versions?
A. Switch with pointers  
B. Switch expressions  
C. Switch arrays  
D. Nested switch removal  

**Answer:** B  
**Explanation:** Modern Java supports switch expressions with cleaner syntax.

### Q150. Which topic is most commonly asked in company Java MCQs?
A. Only GUI design  
B. Only applets  
C. OOP, collections, strings, exceptions, and multithreading  
D. Only graphics programming  

**Answer:** C  
**Explanation:** Most company‑focused Java MCQs target core concepts and practical interview topics.

---

## 9. Java Coding MCQs

### Q151. What is the output of the following code?
```java
public class Test {
    public static void main(String[] args) {
        int a = 5;
        int b = 3;
        a = b;
        b = 10;
        System.out.println(a + " " + b);
    }
}
```
A. 5 3  
B. 3 5  
C. 3 10  
D. 5 10  

**Answer:** C  
**Explanation:** After `a = b`, `a` becomes 3; then `b` is set to 10, so output is `3 10`.

### Q152. What is the output of this code?
```java
public class Test {
    public static void main(String[] args) {
        int x = 10;
        int y = 5;
        System.out.println(x++ + (++y));
    }
}
```
A. 15  
B. 16  
C. 17  
D. 18  

**Answer:** B  
**Explanation:** `x++` returns 10 (then `x` becomes 11), `++y` returns 6; sum is `10 + 6 = 16`.

### Q153. What does this code print?
```java
public class Test {
    public static void main(String[] args) {
        String s1 = "hello";
        String s2 = "hello";
        System.out.println(s1 == s2);
    }
}
```
A. true  
B. false  
C. Exception at runtime  
D. Compilation error  

**Answer:** A  
**Explanation:** Both string literals refer to the same object in the string pool, so `==` returns `true`.

### Q154. What is the output?
```java
public class Test {
    public static void main(String[] args) {
        String s1 = new String("java");
        String s2 = new String("java");
        System.out.println(s1 == s2);
    }
}
```
A. true  
B. false  
C. Exception  
D. Undefined  

**Answer:** B  
**Explanation:** `new String("java")` creates distinct objects, so `s1 == s2` is `false` even though contents are equal.

### Q155. What does this print?
```java
public class Test {
    public static void main(String[] args) {
        int arr[] = {10, 20, 30};
        int total = 0;
        for (int i : arr) {
            total += i;
        }
        System.out.println(total);
    }
}
```
A. 10  
B. 20  
C. 30  
D. 60  

**Answer:** D  
**Explanation:** It sums all elements: `10 + 20 + 30 = 60`.

### Q156. What will be printed?
```java
public class Test {
    public static void main(String[] args) {
        try {
            System.out.print("A");
            int x = 5 / 0;
            System.out.print("B");
        } catch (ArithmeticException e) {
            System.out.print("C");
        } finally {
            System.out.print("D");
        }
    }
}
```
A. A  
B. AB  
C. AC  
D. ACD  

**Answer:** D  
**Explanation:** `A` is printed, the division by `0` throws `ArithmeticException`, so `C` is printed in `catch`, and `D` is printed in `finally`.

### Q157. What is the output?
```java
public class Test {
    public static void main(String[] args) {
        List<Integer> list = new ArrayList<>();
        list.add(1);
        list.add(2);
        list.remove(1);
        System.out.println(list);
    }
}
```
Assume imports are present.

A. [1]  
B. [2]  
C. [1, 2]  
D. []  

**Answer:** A  
**Explanation:** `remove(1)` removes the **element at index 1** (value `2`), so only `1` remains.

### Q158. What is printed?
```java
public class Test {
    static int x = 10;
    {
        x = 25;
    }
    public static void main(String[] args) {
        Test t = new Test();
        System.out.println(x);
    }
}
```
A. 10  
B. 25  
C. 0  
D. Compilation error  

**Answer:** B  
**Explanation:** The instance initializer block runs when the object is created and sets `x = 25`.

### Q159. What does this code print?
```java
public class Test {
    public static void main(String[] args) {
        int a = 10;
        int b = 20;
        int temp = a;
        a = b;
        b = temp;
        System.out.println(a + " " + b);
    }
}
```
A. 10 20  
B. 20 10  
C. 20 20  
D. 10 10  

**Answer:** B  
**Explanation:** Values of `a` and `b` are swapped using `temp`.

### Q160. What is the output?
```java
public class Test {
    public static void main(String[] args) {
        for (int i = 0; i < 3; i++) {
            if (i == 1) continue;
            System.out.print(i);
        }
    }
}
```
A. 012  
B. 02  
C. 01  
D. 12  

**Answer:** B  
**Explanation:** `continue` skips the iteration when `i == 1`, so only `0` and `2` are printed.

### Q161. What is printed?
```java
public class Test {
    public static void main(String[] args) {
        String s = "Hello";
        s.concat(" World");
        System.out.println(s);
    }
}
```
A. Hello  
B. Hello World  
C. World  
D. Compilation error  

**Answer:** A  
**Explanation:** `concat()` returns a new string; the original `s` is unchanged because strings are immutable.

### Q162. What will be printed?
```java
public class Test {
    public static void main(String[] args) {
        String s = new String("Java");
        s = s.intern();
        String t = "Java";
        System.out.println(s == t);
    }
}
```
A. true  
B. false  
C. Exception  
D. Depends on JVM  

**Answer:** A  
**Explanation:** After `intern()`, `s` points to the same string‑pool object as `t`, so `s == t` is `true`.

### Q163. What is the output?
```java
import java.util.*;

public class Test {
    public static void main(String[] args) {
        Set<Integer> set = new HashSet<>();
        set.add(1);
        set.add(1);
        set.add(2);
        System.out.println(set.size());
    }
}
```
A. 1  
B. 2  
C. 3  
D. 0  

**Answer:** B  
**Explanation:** `Set` does not allow duplicates; the second `1` is ignored, so size is 2 (`1` and `2`).

### Q164. What does this print?
```java
public class Test {
    public static void main(String[] args) {
        int a = 5;
        System.out.println(a > 3 ? a++ : --a);
    }
}
```
A. 5  
B. 6  
C. 4  
D. 3  

**Answer:** A  
**Explanation:** `a > 3` is `true`, so the `a++` result (5) is printed; `a` becomes 6, but the printed value is before increment.

### Q165. What is printed?
```java
public class Test {
    public static void main(String[] args) {
        String s = "abc";
        s = s.toUpperCase();
        System.out.println(s);
    }
}
```
A. abc  
B. Abc  
C. ABC  
D. abC  

**Answer:** C  
**Explanation:** `toUpperCase()` converts all letters to uppercase; `s` now points to `"ABC"`.
