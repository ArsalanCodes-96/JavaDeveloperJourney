# JVM, JRE, and JDK

## 📌 What is JVM?

**JVM (Java Virtual Machine)** is a virtual machine that executes Java bytecode. It provides the "Write Once, Run Anywhere" feature by allowing Java programs to run on any platform that has a JVM installed.

### Functions of JVM
- Loads Java bytecode.
- Verifies the code for security.
- Converts bytecode into machine code.
- Executes the program.
- Manages memory through Garbage Collection.

---

## 📌 What is JRE?

**JRE (Java Runtime Environment)** provides the environment required to run Java applications. It includes the JVM and the necessary libraries and files needed for execution.

### JRE Includes:
- JVM (Java Virtual Machine)
- Core Java Libraries
- Supporting files and resources

**Note:** JRE is used only for running Java programs, not for developing them.

---

## 📌 What is JDK?

**JDK (Java Development Kit)** is a complete package used for developing, compiling, and running Java applications. It includes JRE along with development tools.

### JDK Includes:
- JRE (Java Runtime Environment)
- JVM (Java Virtual Machine)
- Java Compiler (`javac`)
- Java Debugger (`jdb`)
- Java Documentation Tool (`javadoc`)
- Other development utilities

**Note:** Developers install the JDK because it contains everything needed to write, compile, and run Java programs.

---

## 🔄 Relationship between JVM, JRE, and JDK

```text
JDK
│
├── JRE
│   │
│   ├── JVM
│   ├── Core Libraries
│   └── Supporting Files
│
└── Development Tools (javac, jdb, javadoc, etc.)
```

### Simple Formula

- **JVM** → Runs Java bytecode.
- **JRE = JVM + Libraries**
- **JDK = JRE + Development Tools**

## 📊 Difference between JVM, JRE, and JDK

| Feature | JVM | JRE | JDK |
|---------|-----|-----|-----|
| Full Form | Java Virtual Machine | Java Runtime Environment | Java Development Kit |
| Purpose | Runs Java bytecode | Provides runtime environment | Develops and runs Java programs |
| Contains JVM | ❌ | ✅ | ✅ |
| Contains JRE | ❌ | ❌ | ✅ |
| Compiler (`javac`) | ❌ | ❌ | ✅ |
| Used By | End users (indirectly) | End users | Java Developers |

## 🚀 Key Takeaways

- JVM executes Java bytecode.
- JRE provides the environment to run Java programs.
- JDK provides all tools required to develop and run Java applications.
- Every JDK contains a JRE, and every JRE contains a JVM.

---
📚 **Part of my Java Developer Journey.**