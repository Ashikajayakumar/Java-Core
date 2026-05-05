

# 📘 4. Set

The **Set interface** is part of the Java Collections Framework used to store **unique elements only**.

👉 It does not allow duplicates and is used when uniqueness of data is important.



# 🔷 📂 Set Topics

## 📌 Core Concepts

* 📄 [Set Basics](./01.Set-Basic.md)
* 📄 [HashSet](./02.Hashset.md)
* 📄 [LinkedHashSet](./03.LinkedHashSet.md)
* 📄 [Sorted Set (TreeSet)](./04.Sorted%20Set%28TreeSet%29.md)
* 📄 [EnumSet](./05.EnumSet.md)


# 🔷 📌 Key Features of Set

* ✔ Stores **only unique elements**
* ❌ No duplicate values allowed
* ❌ No index-based access
* ✔ Part of `java.util` package
* ✔ Implements `Collection` interface



# 🔷 📌 Set Hierarchy

```text id="set_hierarchy3"
          Collection
               ↓
              Set (Interface)
     ┌─────────┼──────────┬──────────┐
     ↓         ↓          ↓          ↓
 HashSet  LinkedHashSet  TreeSet   EnumSet
```


# 🔷 📌 Types of Set in Java

## 🔹 1. HashSet

* Uses hashing technique
* ❌ No insertion order
* ✔ Fast performance
* ✔ Allows one null value

👉 Best for **fast lookup without ordering**



## 🔹 2. LinkedHashSet

* Maintains **insertion order**
* Uses Hash table + Linked list
* Slightly slower than HashSet
* ✔ Allows one null value

👉 Best for **ordered unique data**



## 🔹 3. TreeSet (Sorted Set)

* Stores elements in **sorted order (ascending)**
* Uses **Red-Black Tree internally**
* ❌ Does not allow null values

👉 Best for:

* Sorting data automatically
* Range-based operations



## 🔹 4. EnumSet

* Used only with **Enum types**
* Very fast and memory efficient
* Internally uses bit vectors

👉 Best for:

* Fixed set of constants (like DAYS, STATUS, TYPE)


# 🔷 📌 HashSet vs LinkedHashSet vs TreeSet vs EnumSet

| Feature      | HashSet | LinkedHashSet | TreeSet     | EnumSet        |
| ------------ | ------- | ------------- | ----------- | -------------- |
| Order        | No      | Insertion     | Sorted      | Enum order     |
| Speed        | Fast    | Medium        | Slow        | Very Fast      |
| Null Allowed | Yes     | Yes           | No          | No             |
| Use Case     | General | Ordered data  | Sorted data | Enum constants |




