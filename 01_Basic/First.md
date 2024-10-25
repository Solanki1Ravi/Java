# class
- class keyword is used to declare a class in Java.

# public keyword
- public keyword is an access modifier that represents visibility. It means it is visible to all.

# static
- static is a keyword. If we declare any method as static, it is known as the static method. The core advantage of the static method is that there is no need to create an object to invoke the static method. The main() method is executed by the JVM, so it doesn't require creating an object to invoke the main() method. So, it saves memory.

# void
- void is the return type of the method. It means it doesn't return any value.
main represents the starting point of the program.

# String[] args
- String[] args or String args[] is used for command line argument.

# System.out.println()
- System.out.println() is used to print statement. Here, System is a class, out is an object of the PrintStream class, println() is a method of the PrintStream class. We will discuss the internal working of System.out.println() statement in the coming section.

# import java.util.*;
- this means import everything from the util

# Scanner

- scanner is used to take the user input in out program

# system.in
- take the input from system

---
# if we change the name of main method
``` java

public class Main {
    public static void Mymain(String[] args) {
        System.out.println("Ravindra Singh");
        
    }
    
}



```
- Output main method not found in class Main.

# If We change the name of the file

``` java 

public class MyMain {
    public static void main(String[] args) {
        System.out.println("Ravindra Singh");
        
    }
    
}


output file not found
```