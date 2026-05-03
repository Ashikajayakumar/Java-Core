

# 📘 1. Collection - Basics (Java)

The **Java Collection Framework (JCF)** provides a set of interfaces and classes to store and manipulate groups of objects efficiently.

👉 It is part of `java.util` package.



# 🔷 📂 Collection Basics Topics

## 📌 Core Concepts

* 📄 [Collection Interface](./01.Collection%20.md)
* 📄 [Generic vs Non-Generic](./02.Generic%20VS%20Non-Generic.md)
* 📄 [Extends vs Implements (Interface)](./03.Extends%20vs%20Interface%20.md)
* 📄 [Cursor](./1.Collection%20-%20Basic%20/04.Cursor.md)



# 🔷 📌 What is Collection?

A **Collection** in Java is a framework that provides:

* ✔ Data storage
* ✔ Data manipulation
* ✔ Standard operations (add, remove, search)



## 🔹 Key Features

* ✔ Part of `java.util`
* ✔ Framework for data structures
* ✔ Supports dynamic data handling
* ❌ Does not include primitive types (uses objects only)



# 🔷 📌 Collection Hierarchy

```text id="collection_hierarchy"
                Iterable
                    ↓
               Collection (Interface)
     ┌────────────┼────────────┐
     ↓            ↓            ↓
    List         Set          Queue
```


# 🔷 📌 Topics Explained

## 🔹 1. Collection Interface

* Root interface of Java Collection Framework
* Defines common methods like:

  * add()
  * remove()
  * size()
  * clear()



## 🔹 2. Generic vs Non-Generic

### 🔷 Non-Generic (Old Style)

```java
ArrayList list = new ArrayList();
list.add("Java");
list.add(100); // different types allowed
```

✔ Allows multiple data types
❌ Type safety problem

---

### 🔷 Generic (Modern Style)

```java
ArrayList<String> list = new ArrayList<>();
list.add("Java");
// list.add(100); ❌ Not allowed
```

* ✔ Type safety
* ✔ No runtime errors
* ✔ Cleaner code


## 🔹 3. Extends vs Implements

| Keyword    | Used For                              | Meaning                 |
| ---------- | ------------------------------------- | ----------------------- |
| extends    | Class → Class / Interface → Interface | Inheritance             |
| implements | Class → Interface                     | Contract implementation |

---

### 🔷 Example

```java
class A extends B { }      // class inheritance

class A implements B { }   // interface implementation
```

