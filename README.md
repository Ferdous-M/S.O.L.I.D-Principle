# SOLID Principles in Java

A practical Java project demonstrating the **SOLID principles of object-oriented design** through simple, focused, and easy-to-understand examples.

The project focuses on how SOLID principles can be applied to build software that is **maintainable, extensible, testable, reusable, and loosely coupled**.

---

## 📌 What is SOLID?

**SOLID** is an acronym for five fundamental principles of object-oriented design, introduced and popularized through the work of **Robert C. Martin (Uncle Bob)**.

| Principle | Meaning                         |
| --------- | ------------------------------- |
| **S**     | Single Responsibility Principle |
| **O**     | Open/Closed Principle           |
| **L**     | Liskov Substitution Principle   |
| **I**     | Interface Segregation Principle |
| **D**     | Dependency Inversion Principle  |

Together, these principles provide guidelines for designing software components with **clear responsibilities, minimal coupling, and well-defined abstractions**.

---

## 📚 Principles Covered

### 1. Single Responsibility Principle (SRP)

> A class should have one responsibility and only one reason to change.

SRP encourages separating unrelated responsibilities into different classes instead of placing multiple responsibilities inside a single class.

**Key benefits:**

* Easier maintenance
* Improved readability
* Easier unit testing
* Reduced coupling
* Better code organization

---

### 2. Open/Closed Principle (OCP)

> Software entities should be open for extension but closed for modification.

The Open/Closed Principle encourages designing classes so that new behavior can be added without repeatedly modifying existing, stable code.

**Key benefits:**

* Easier feature extension
* Reduced risk of breaking existing functionality
* Better scalability
* Encourages abstraction and polymorphism

---

### 3. Liskov Substitution Principle (LSP)

> Subtypes should be substitutable for their base types without changing the correctness of the program.

LSP ensures that derived classes correctly honor the behavior and expectations defined by their parent classes or interfaces.

**Key benefits:**

* Reliable inheritance
* Better polymorphism
* More predictable behavior
* Reduced unexpected side effects

---

### 4. Interface Segregation Principle (ISP)

> Clients should not be forced to depend on interfaces they do not use.

ISP encourages creating **small, focused interfaces** instead of large interfaces containing unrelated methods.

**Key benefits:**

* Smaller interfaces
* Reduced unnecessary dependencies
* Easier implementation
* Better flexibility

---

### 5. Dependency Inversion Principle (DIP)

> High-level modules should not depend on low-level modules. Both should depend on abstractions.

DIP encourages applications to depend on **interfaces or abstractions rather than concrete implementations**.

**Key benefits:**

* Loose coupling
* Easier testing and mocking
* Easier replacement of implementations
* Better maintainability
* Greater flexibility

---

## 🏗️ Project Structure

The project contains separate examples for each SOLID principle:

```text
src/
└── main/
    └── java/
        └── ...
            ├── SRP/
            ├── OCP/
            ├── LSP/
            ├── ISP/
            └── DIP/
```

Each example demonstrates a specific design problem and how applying the corresponding SOLID principle can improve the design.

---

## 🎯 Learning Objectives

This project was created to develop a practical understanding of:

* Object-oriented design principles
* Separation of responsibilities
* Abstraction and encapsulation
* Inheritance and polymorphism
* Interfaces and dependency management
* Loose coupling
* Extensible software design
* Maintainable and testable code

---

## 🛠️ Technologies

* **Java**
* **Object-Oriented Programming (OOP)**
* **SOLID Design Principles**

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Ferdous-M/S.O.L.I.D-Principle.git
```

### Open the project

Open the project in your preferred Java IDE, such as:

* IntelliJ IDEA
* Eclipse
* Visual Studio Code

### Run the examples

Navigate to the corresponding example for each principle and run the Java classes to observe how the design changes when SOLID principles are applied.

---

## 💡 Why SOLID Matters

SOLID principles are particularly useful when developing applications that need to evolve over time.

Applying these principles can help developers:

```text
Clear Responsibilities
        ↓
Loose Coupling
        ↓
Easier Testing
        ↓
Safer Changes
        ↓
More Maintainable Software
```

They are especially relevant when working with larger applications, layered architectures, and frameworks such as **Spring Boot**, where dependency injection, interfaces, and separation of concerns are commonly used.

---

## 📖 Summary

| Principle | Main Idea                                            |
| --------- | ---------------------------------------------------- |
| **SRP**   | One class → One responsibility                       |
| **OCP**   | Extend behavior without modifying stable code        |
| **LSP**   | Subtypes should be safely substitutable              |
| **ISP**   | Prefer small, focused interfaces                     |
| **DIP**   | Depend on abstractions, not concrete implementations |

---



---

⭐ If you find this project useful, consider giving it a star!
