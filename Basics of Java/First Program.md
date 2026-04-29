                                          2.First Program & Basic Structure
                                               

<h2 align="center"><b>🔹 1. public class name must match file name </b></h2>

If file name is:
```
Hello.java
```
Class name must be:
```
public class Hello
```
##
❌ If names don’t match → compile error.

✔ Only one public class per file
✔ Case-sensitive (Hello ≠ hello)


<h2 align ="centre"><b>🔹 2. public static void main(String[] args)— Entry Point</b></h2>

This is the starting point of program execution.

JVM always looks for this method.
```
| Part            | Meaning                         |
|-----------------|---------------------------------|
| public          | Accessible from anywhere        |
| static          | No object needed to call method |
| void            | Does not return any value       |
| main            | Method name recognized by JVM   |
| String[] args   | Command-line arguments          |

```
Without main() → program won’t run.


<h2 align ="centre"><b>🔹 3. Output Statements</b></h2>

```🔸 System.out.println()```

Prints text and moves to next line.
```
System.out.println("Hello");
System.out.println("World");
```

Output:
```
Hello
World
```
🔸 ```System.out.print()```

Prints text on the same line.
```
System.out.print("Hello ");
System.out.print("World");
```

Output:
```
Hello World
```


<h2 align ="centre"><b>🔹 4. Comments in Java</b></h2>

Used to explain code. Compiler ignores them.

🔸 Single-line comment
```
// This is a comment
```
🔸 Multi-line comment
```
/* This is
   a multi-line
   comment */
```

🧠 Full Example Program
```
public class Hello {

    // Main method — program starts here
    public static void main(String[] args) {

        System.out.println("Hello World"); // prints text

    }
}
```
This structure = base of all Java programs 🏗
