# 📌 Queue Implementation (clsMyQueue) ⚡

> **A C++ template-based queue implementation using a doubly linked list, providing essential queue operations such as enqueue, dequeue, and traversal. 🚀**

---

## 🌟 Project Overview

The `clsMyQueue` class is a **generic queue** implementation in C++ built on top of a doubly linked list (`clsDblLinkedList`). This allows efficient dynamic memory management and extends the standard queue functionalities with additional features.

### 🔹 Core Functionalities:
- **Push (Enqueue)** elements to the back of the queue 🔄
- **Pop (Dequeue)** elements from the front ❌
- **Access Front & Back** elements directly 🔍
- **Check Queue Size & Emptiness** 📏
- **Reverse & Modify** elements within the queue 🔄
- **Insert & Update** elements at specific positions ✏️
- **Clear** the entire queue in one function call ✨

This queue implementation is **generic**, meaning it can store any data type using C++ templates.

---

## ✨ Features

### 🔹 Basic Queue Operations
- **`Push(Value)`**: Adds an element to the back of the queue.
- **`Pop()`**: Removes the front element of the queue.
- **`Front()`**: Retrieves the first element in the queue.
- **`Back()`**: Retrieves the last element in the queue.
- **`Size()`**: Returns the number of elements in the queue.
- **`IsEmpty()`**: Checks if the queue is empty.
- **`Print()`**: Displays the queue elements.

### 🔹 Extended Functionalities
- **`GetItem(Index)`**: Retrieves the value of an element at a specific index.
- **`Reverse()`**: Reverses the order of the queue.
- **`UpdateItem(Index, NewValue)`**: Updates the value of an element at a given index.
- **`InsertAfter(Index, Value)`**: Inserts an element after a specific index.
- **`InsertAtFront(Value)`**: Inserts an element at the front of the queue.
- **`InsertAtBack(Value)`**: Inserts an element at the back of the queue.
- **`Clear()`**: Removes all elements from the queue.

---

## 🚀 How It Works

### 🔹 Enqueue & Dequeue
- Elements are added using `Push(Value)` at the **end**.
- Elements are removed using `Pop()` from the **front**.

### 🔹 Accessing Elements
- `Front()` and `Back()` allow **direct access** to queue ends.
- `GetItem(Index)` retrieves an element at a given position.

### 🔹 Modifications & Reversal
- `UpdateItem(Index, NewValue)` modifies an existing value.
- `Reverse()` swaps all node links to **reverse** the queue.
- `InsertAfter(Index, Value)`, `InsertAtFront(Value)`, and `InsertAtBack(Value)` allow **custom insertions**.

### 🔹 Memory Management
- The queue dynamically allocates memory for new elements.
- `Clear()` safely removes all elements to prevent memory leaks.

---

## 📚 Potential Enhancements

- 🏗 **Iterator Support**: Implementing iterators for STL-like traversal.
- ⏳ **Time Complexity Optimization**: Enhancing performance for large datasets.
- 🗃️ **Persistent Storage**: Implementing file handling for saving queue data.
- 🚀 **Thread Safety**: Making the queue thread-safe for concurrent operations.

---

## ⚙️ Technologies Used

- **Language**: C++
- **Templates**: Enables the queue to store any data type
- **Doubly Linked List**: Ensures efficient insertion and deletion
- **Dynamic Memory Allocation**: Uses pointers for flexible data storage

---

## 🎯 Learning Outcomes

This project demonstrates:
- ✅ **Queue operations (enqueue, dequeue, front, back, size, empty check)**
- ✅ **Generic programming with C++ templates**
- ✅ **Linked list-based queue implementation for dynamic storage**
- ✅ **Efficient memory management with pointers**

---

## 📜 License

This project is **open-source**. Feel free to modify and enhance it! 🚀

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for improvements, submit a Pull Request.

---

## 🏁 Ready to Explore?

### 🚀 How to Run
1. **Download** the repository.
2. **Include** `clsMyQueue.h` in your project.
3. **Compile & Run** your C++ program with a standard compiler (e.g., `g++ main.cpp -o output`).
4. **Test** different queue operations.

---

