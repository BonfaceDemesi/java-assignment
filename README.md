Section 1:
    1. Explain the differences between primitive and reference data types. 
Primitive data types: These store actual values and are predefined by the programming language. They include types like int, char, boolean, float, etc. They have fixed sizes and are stored in the stack. Example: int age = 25;.
Reference data types: These store references (addresses) to objects. They are created using constructors or new keyword and can be of any class type like String, Array, Object. Reference types are stored in the heap. Example: String name = "John";.
    2. Define the scope of a variable (hint: local and global variable)
Local variables: These are declared within a method, constructor, or block, and can only be accessed within that method or block.
Global (Instance) variables: These are declared within a class but outside methods. They can be accessed by any method in the class. If they are static, they belong to the class itself and not instances.
    3. Why is initialization of variables required. 
Initialization of variables is required to provide an initial value to a variable before it is used. This prevents undefined behavior and errors that could arise from trying to use variables that contain garbage values.
    4. Differentiate between static, instance and local variables. 
i. Static variables: Belong to the class and are shared among all instances of the class. Changes made to a static variable affect all instances.
ii. Instance variables: Are associated with an instance (object) of a class. Each object has its own copy of instance variables.
iii. Local variables: Are declared inside a method and can only be used within that method.
    5. Differentiate between widening and narrowing casting in java. 
i. Widening casting: Converting a smaller data type to a larger one (e.g., int to long, float to double). It’s done automatically by Java.
ii. Narrowing casting: Converting a larger data type to a smaller one (e.g., double to float, int to byte). It requires explicit casting and may cause data loss.
    6. the following table shows data type, its size, default value and the range. Filling in the missing values.
