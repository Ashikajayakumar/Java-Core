

# 📘 5. Map (Java Collections Framework)

The **Map interface** in Java stores data in **key–value pairs**, where each key is unique.

👉 It is part of `java.util` package and widely used for fast data retrieval.



# 🔷 📂 Map Topics

## 📌 Core Concepts

* 📄 [Map Basics](./01.Map-Basic.md)
* 📄 [Hashtable](./02.HashTable.md)
* 📄 [HashMap](./03.HashMap.md)
* 📄 [HashTable vs HashMap](./04.HashTable%20vs%20HashMap.md)
* 📄 [LinkedHashMap](./05.LinkedHashMap.md)
* 📄 [Sorted Map (TreeMap)](./06.Sorted%20Map%28TreeMap%29.md)



# 🔷 📌 Key Features of Map

* ✔ Stores data in **key → value pairs**
* ✔ Keys are **unique**
* ✔ Values can be duplicated
* ❌ Does NOT extend Collection interface
* ✔ Provides fast lookup using keys



# 🔷 📌 Map Hierarchy

```text
            Map (Interface)
      ┌────────┼──────────┐
      ↓        ↓          ↓
  HashMap   LinkedHashMap  TreeMap
      ↓
  Hashtable (legacy)
```



# 🔷 📌 Types of Map Implementations

## 🔹 1. HashMap

* Fast performance
* No order guarantee
* Allows one null key


## 🔹 2. Hashtable

* Thread-safe (synchronized)
* Slower than HashMap
* Does NOT allow null keys/values



## 🔹 3. LinkedHashMap

* Maintains insertion order
* Slightly slower than HashMap



## 🔹 4. TreeMap

* Sorted by key (ascending order)
* Implements Red-Black Tree
* No null keys allowed



# 🔷 📌 Quick Comparison

| Map Type      | Order           | Thread Safe | Speed  |
| ------------- | --------------- | ----------- | ------ |
| HashMap       | No              | No          | Fast   |
| Hashtable     | No              | Yes         | Slow   |
| LinkedHashMap | Insertion order | No          | Medium |
| TreeMap       | Sorted order    | No          | Slow   |

