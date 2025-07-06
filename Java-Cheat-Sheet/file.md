# ☕ Java Cheat Sheet

A complete and beginner-friendly **Java Cheat Sheet** for quick reference. This guide covers Java syntax, data types, OOP, collections, exceptions, and more!

---

## 📌 Table of Contents

- [Basic Syntax](#-basic-syntax)
- [Data Types](#-data-types)
- [Operators](#-operators)
- [Control Statements](#-control-statements)
- [Arrays](#-arrays)
- [OOP (Object-Oriented Programming)](#-oop-object-oriented-programming)
- [Exception Handling](#-exception-handling)
- [Collections](#-collections)
- [User Input](#-user-input)
- [Useful Methods](#-useful-methods)
- [Resources](#-resources)
- [Author](#-author)

---

## 🔤 Basic Syntax

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```
```
🔢 Data Types
int age = 20;
double price = 99.99;
char grade = 'A';
boolean isJavaFun = true;
String name = "Ishan";
```
```
➕ Operators

+  -  *  /  %       // Arithmetic
== != > < >= <=     // Comparison
&& || !             // Logical
= += -= *= /=       // Assignment
```
```
🔁 Control Statements
✅ If-Else

if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
```
```
🔄 Switch
switch (day) {
    case 1: System.out.println("Sunday"); break;
    case 2: System.out.println("Monday"); break;
    default: System.out.println("Invalid day");
}
```
```
🔂 Loops
For Loop
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```
```
While Loop
int i = 0;
while (i < 5) {
    System.out.println(i);
    i++;
}
```
```
Do-While Loop
int i = 0;
do {
    System.out.println(i);
    i++;
} while (i < 5);
```
```
📦 Arrays
int[] numbers = {1, 2, 3, 4};
System.out.println(numbers[0]);

String[] names = new String[3];
names[0] = "Ishan";
```
```
🧱 OOP (Object-Oriented Programming)
✅ Class & Object
class Car {
    String color = "Red";
}
Car myCar = new Car();
System.out.println(myCar.color);
```
```
🛠 Constructor

class Student {
    Student() {
        System.out.println("Constructor called");
    }
}
```
```
🧬 Inheritance
class Animal {
    void sound() {
        System.out.println("Animal sound");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Dog barks");
    }
}
```
```
📚 Polymorphism
class Animal {
    void sound() {
        System.out.println("Animal sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }
}

```
```
🔒 Abstraction
abstract class Shape {
    abstract void draw();
}
```

```
📡 Interface
interface Animal {
    void makeSound();
}

class Cat implements Animal {
    public void makeSound() {
        System.out.println("Meow");
    }
}
```
```
⚠️ Exception Handling
try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Can't divide by zero");
} finally {
    System.out.println("Always executes");
}
```
```
📚 Collections
ArrayList
import java.util.ArrayList;

ArrayList<String> list = new ArrayList<>();
list.add("Apple");
list.add("Banana");
System.out.println(list.get(0));
```
```
HashMap
import java.util.HashMap;

HashMap<String, Integer> marks = new HashMap<>();
marks.put("Math", 90);
System.out.println(marks.get("Math"));
```
```
⌨️ User Input
import java.util.Scanner;

Scanner sc = new Scanner(System.in);
System.out.print("Enter name: ");
String name = sc.nextLine();
System.out.println("Hello " + name);
```
```
🧠 Useful Methods
str.length();
str.toLowerCase();
Math.max(10, 20);
Math.sqrt(64);
arr.length;
list.size();
```
```
🌐 Resources
📖 Java Official Docs

🎓 W3Schools Java

🔗 JavaTPoint
```
```  
👨‍💻 Author
Ishan Walia
🚀 B.Tech CSE | App & Web Developer | Cybersecurity Learner
🌐 GitHub
🔗 LinkedIn
```
```
📄 License
Free to use under MIT License.
```
```
yaml



### ✅ Ready to upload!

Yeh cheat sheet tumhare **Java repository**, **Marko learning project**, ya **personal documentation** ke liye perfect hai.  
Batao agar tumhein chahiye:

- Java MCQs  
- Java Mini Projects Ideas  
- Java Advanced Topics like Threads, JDBC, File Handling  
- PDF version bhi export karna chaho toh bata dena

Want me to create a **thumbnail/banner** for this README too?

```






