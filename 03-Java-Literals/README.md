# Day 03 - Java Literals

## 📖 Introduction

In Java, a **literal** is a fixed value that is written directly in the source code. These values are assigned to variables and remain constant unless the variable is changed. Literals are one of the basic building blocks of any Java program.

### Example

```java
int age = 18;
double pi = 3.14159;
char grade = 'A';
boolean isJavaFun = true;
String name = "Arsalan";
```

In the above example, `18`, `3.14159`, `'A'`, `true`, and `"Arsalan"` are all literals.

---

## 🔹 Types of Literals in Java

### 1. Integer Literals

Integer literals represent whole numbers without any decimal point.

**Examples:**

```java
int a = 10;
int b = 250;
```

Java supports different formats for integer literals:

* **Decimal:** `100`
* **Binary:** `0b1010`
* **Octal:** `012`
* **Hexadecimal:** `0x1A`

---

### 2. Floating-Point Literals

Floating-point literals represent numbers with decimal points.

**Examples:**

```java
float f = 10.5f;
double d = 99.99;
```

> **Note:** A `float` literal must end with `f` or `F`. By default, decimal values are treated as `double`.

---

### 3. Character Literals

Character literals represent a single character enclosed in single quotes (`' '`).

**Examples:**

```java
char ch = 'A';
char digit = '7';
char symbol = '#';
```

---

### 4. String Literals

A string literal is a sequence of characters enclosed in double quotes (`" "`).

**Examples:**

```java
String language = "Java";
String message = "Hello, World!";
```

---

### 5. Boolean Literals

Boolean literals represent one of two possible values:

* `true`
* `false`

**Example:**

```java
boolean isStudent = true;
boolean isPassed = false;
```

---

### 6. Null Literal

The `null` literal represents the absence of an object reference.

**Example:**

```java
String str = null;
```

---

## 💻 Example Program

```java
public class JavaLiterals {
    public static void main(String[] args) {

        int age = 18;
        float percentage = 92.5f;
        char grade = 'A';
        boolean passed = true;
        String name = "Arsalan";

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Percentage: " + percentage);
        System.out.println("Grade: " + grade);
        System.out.println("Passed: " + passed);
    }
}
```

### Output

```
Name: Arsalan
Age: 18
Percentage: 92.5
Grade: A
Passed: true
```

---

## 📝 Key Points

* A literal is a fixed value written directly in the Java code.
* Java provides six main types of literals:

  1. Integer Literals
  2. Floating-Point Literals
  3. Character Literals
  4. String Literals
  5. Boolean Literals
  6. Null Literal
* Character literals use **single quotes (`' '`)**.
* String literals use **double quotes (`" "`)**.
* Decimal values are `double` by default.
* A `float` value must end with `f` or `F`.

---

## 🎯 Conclusion

Java literals are the constant values used throughout a program. Understanding different types of literals is essential because they are used while declaring variables, performing calculations, and writing real-world Java applications. A strong understanding of literals forms the foundation for learning variables, data types, and expressions in Java.

---

**📅 Day 03 of My Java Developer Journey**
