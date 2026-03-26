
# Generalized Data Structure Library (GDSL)

![C++](https://img.shields.io/badge/language-C%2B%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

A comprehensive **Generalized Data Structure Library (GDSL)** implemented in **C++** using **templates** to provide reusable, type-safe, and efficient implementations of commonly used data structures. Ideal for **learning, projects, and competitive programming**.

---

## 📂 Project Structure

```

Generalized-Data-Structure-Library
│
├── library
│   └── gdsl.cpp             # All data structures implemented here
│
├── examples
│   └── demo.cpp             # Example usage of the library
│
├── docs
│   └── project_overview.md  # Documentation and overview of data structures
│
├── README.md                # Project description and guide
├── LICENSE                  # MIT License
└── .gitignore               # Git ignore file

````

---

## 🔹 Features

The library includes **generic implementations** of:

| Type                  | Node Class         | Functionality Class  |
|----------------------|------------------|-------------------|
| Singly Linear         | `SinglyLLLnode`  | `SinglyLLL`       |
| Singly Circular       | `SinglyCLLnode`  | `SinglyCLL`       |
| Doubly Linear         | `DoublyLLLnode`  | `DoublyLLL`       |
| Doubly Circular       | `DoublyCLLnode`  | `DoublyCLL`       |
| Stack                 | `Stacknode`      | `Stack`           |
| Queue                 | `Queuenode`      | `Queue`           |

### ✅ Supported Operations
- **Insertion:** At beginning, end, or any position
- **Deletion:** From beginning, end, or any position
- **Display:** Print elements in order
- **Count:** Get number of elements
- **Stack & Queue:** Standard push/pop/enqueue/dequeue operations

---

## 🌟 Project Highlights / Key Strengths

- **Generic Templates:** Fully type-safe implementations using C++ templates.
- **Reusable & Modular:** Single file (`gdsl.cpp`) can be included in any project.
- **Complete Coverage:** Includes all common linear and circular data structures.
- **Clean Interface:** Simple and consistent function naming for all structures.
- **Documentation Ready:** Functions are documented, making it beginner-friendly.
- **Efficient & Lightweight:** Minimal memory overhead, optimized operations.
- **Example-driven:** `examples/demo.cpp` shows usage of all data structures.

---

## 💻 Example Usage

```cpp
#include "../library/gdsl.cpp"

int main() {
    SinglyLLL<int> list;

    list.InsertFirst(10);
    list.InsertLast(20);
    list.InsertAtPos(15, 2);
    list.Display();        // Output: | 10 | -> | 15 | -> | 20 | -> NULL

    list.DeleteAtPos(2);
    list.Display();        // Output: | 10 | -> | 20 | -> NULL

    cout << "Total nodes: " << list.Count() << endl;
    return 0;
}
````

---

## 📖 Documentation

Detailed documentation for each data structure and its functions is available in the `docs/project_overview.md`.

---

## 🛠️ Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/<your-username>/Generalized-Data-Structure-Library.git
```

2. **Compile the library and demo:**

```bash
g++ examples/demo.cpp -o demo
./demo
```

3. **Include `gdsl.cpp`** in your own projects to use the data structures.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## ✨ Author

**Aashish Vilas Labade**

* GitHub: 
* Email: aashishlabade2004@gmail.com

```
