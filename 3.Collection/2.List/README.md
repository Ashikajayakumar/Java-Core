

# 📘 2. List (Java Collections Framework)

The **List interface** in Java is part of the Collection Framework used to store **ordered elements**.

👉 It allows **duplicate elements** and maintains **insertion order**.



# 🔷 📂 List Topics

## 📌 Core Concepts

* 📄 [List Basics](./01.List.md)
* 📄 [ArrayList](./02.ArrayList.md)
* 📄 [LinkedList](./03.Linked%20List.md)
* 📄 [Vector (Stack)](./04.Vector%28Stack%29.md)


# 🔷 📌 Key Features of List

* ✔ Maintains **insertion order**
* ✔ Allows **duplicate elements**
* ✔ Indexed access supported
* ✔ Part of `java.util` package
* ✔ Implements `Collection` interface



# 🔷 📌 List Hierarchy

```text id="list_hierarchy"
          Collection
               ↓
              List (Interface)
     ┌─────────┼──────────┬──────────┐
     ↓         ↓          ↓          ↓
 ArrayList  LinkedList   Vector     Stack
```



# 🔷 📌 Types of List in Java

## 🔹 1. ArrayList

* Dynamic array implementation
* Fast for searching (random access)
* Slow for insertion/deletion in middle



## 🔹 2. LinkedList

* Doubly linked list implementation
* Fast insertion/deletion
* Slower random access



## 🔹 3. Vector

* Synchronized (thread-safe)
* Slower than ArrayList
* Legacy class



## 🔹 4. Stack

* Follows **LIFO (Last In First Out)**
* Extends Vector class
* Used for undo operations, recursion


# 🔷 📌 Comparison Table

| Type       | Order | Duplicate | Speed                | Use Case      |
| ---------- | ----- | --------- | -------------------- | ------------- |
| ArrayList  | Yes   | Yes       | Fast (search)        | Random access |
| LinkedList | Yes   | Yes       | Fast (insert/delete) | Dynamic data  |
| Vector     | Yes   | Yes       | Slow                 | Thread-safe   |
| Stack      | Yes   | Yes       | LIFO                 | Backtracking  |

---

---

If you want next, I can also create:
✅ Full **Queue README (same format)**
✅ Full **Map README (same format)**
✅ OR complete **Java Collections Framework master README (List + Set + Map + Queue)** 🚀
