

# 📘 3. Queue (Java Collections Framework)

The **Queue interface** in Java is used to store elements in a **FIFO (First In First Out)** order.

👉 It is part of `java.util` package and is widely used in scheduling, buffering, and task management systems.



# 🔷 📂 Queue Topics

## 📌 Core Concepts

* 📄 [Queue Basics (Types)](./01.Queue%20-%20Basic%28Types%29%20.md)
* 📄 [LinkedList as Queue](./02.LinkedList%28Queue%29.md)
* 📄 [PriorityQueue](./03.Priority%20Queue.md)
* 📄 [ArrayDeque](./04.ArrayDeque.md)



# 🔷 📌 What is Queue?

A **Queue** is a linear data structure that follows:

## 👉 FIFO Principle (First In First Out)

```text id="queue_flow"
Front → [10] → [20] → [30] ← Rear
         ↑                 ↑
      Remove            Insert
```

* ✔ First element inserted is removed first
* ✔ New elements are added at the rear
* ✔ Elements are accessed from the front

# 🔷 📌 Key Features of Queue

* ✔ Follows FIFO order
* ✔ Part of Collection Framework
* ✔ Used for processing tasks in order
* ❌ No random access (like index-based access)



# 🔷 📌 Queue Hierarchy

```text id="queue_hierarchy"
           Collection
                ↓
              Queue (Interface)
     ┌──────────┼────────────┐
     ↓          ↓            ↓
 LinkedList  PriorityQueue  ArrayDeque
```



# 🔷 📌 Types of Queue in Java

## 🔹 1. Queue (Basic Types)

### Types of Queue:

* Simple Queue (Linear Queue)
* Circular Queue
* Priority Queue
* Deque (Double Ended Queue)

👉 Used based on structure and requirement



## 🔹 2. LinkedList as Queue

* Implements Queue interface
* Works as FIFO structure
* Dynamic size (no fixed limit)

```java id="queue_linkedlist"
import java.util.*;

public class Demo {
    public static void main(String[] args) {

        Queue<Integer> q = new LinkedList<>();

        q.add(10);
        q.add(20);
        q.add(30);

        System.out.println(q);   // [10, 20, 30]

        q.remove(); // removes 10

        System.out.println(q);
    }
}
```


## 🔹 3. PriorityQueue

* Elements are processed based on **priority**
* NOT FIFO
* Smallest element has highest priority (default)

```java id="priority_queue"
import java.util.*;

public class Demo {
    public static void main(String[] args) {

        Queue<Integer> pq = new PriorityQueue<>();

        pq.add(50);
        pq.add(10);
        pq.add(30);

        System.out.println(pq); // internal order not sorted view

        System.out.println(pq.poll()); // 10 (highest priority)
    }
}
```

---

## 🔹 4. ArrayDeque

* Double-ended queue (Deque)
* Faster than LinkedList
* Can insert/remove from both ends

```java id="arraydeque"
import java.util.*;

public class Demo {
    public static void main(String[] args) {

        Deque<Integer> dq = new ArrayDeque<>();

        dq.addFirst(10);
        dq.addLast(20);
        dq.addLast(30);

        System.out.println(dq); // [10, 20, 30]

        dq.removeFirst(); // removes 10

        System.out.println(dq);
    }
}
```

