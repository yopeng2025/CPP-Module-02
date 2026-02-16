# CPP Module 02 - Ad-hoc Polymorphism & Fixed-point Numbers

### Project Description
 **"An exploration of Fixed-point arithmetic, Operator Overloading, and the Orthodox Canonical Class Form in C++."**

---

## 🧠 Key Learning Objectives

* **🟢 Orthodox Canonical Form**: Implementing the four essential member functions to ensure robust class behavior and resource safety.
* **🔵 Fixed-point Representation**: Understanding the mechanics of fractional bits and how they differ from floating-point numbers.
* **🟡 Operator Overloading**: Redefining the behavior of arithmetic, comparison, and increment operators for custom types.
* **🟣 Ad-hoc Polymorphism**: Utilizing function overloading to provide multiple implementations of the same operation.

---

## 📂 Exercise Breakdown

### 🟢 Ex00: My First Class in Orthodox Canonical Form
* **Goal**: Implement a `Fixed` class that stores a fixed-point value using an integer.
* **Concepts**:
    * Adhering to the **Orthodox Canonical Form** (Default Constructor, Copy Constructor, Assignment Operator, Destructor).
    * Understanding the `static const int` for fractional bits.
    * Managing raw bits without complex conversions yet.

### 🔵 Ex01: Towards a more useful fixed-point number class
* **Level**: **Intermediate**
* **Goal**: Expand the class to convert between `int`/`float` and fixed-point values.
* **Concepts**:
    * **Bitwise Shifting**: Using `<<` and `>>` to scale values into fixed-point format.
    * **Insertion Operator Overloading**: Overloading the `<<` operator to allow printing via `std::cout`.
    * Mathematics of rounding and scaling factors ($2^n$).

### 🟡 Ex02: Now we’re talking
* **Level**: **Advanced**
* **Goal**: Overload a wide range of operators to make the class behave like a built-in numeric type.
* **Concepts**:
    * **Arithmetic Operators**: `+`, `-`, `*`, `/`.
    * **Comparison Operators**: `>`, `<`, `>=`, `<=`, `==`, `!=`.
    * **Increment/Decrement**: Differentiating between pre-increment (`++i`) and post-increment (`i++`).
    * **Static Member Functions**: Implementing `min` and `max` overloads for `const` and non-const references.

### 🟣 Ex03: BSP (Binary Space Partitioning)
* **Level**: **Expert**
* **Goal**: Determine if a point is located inside a triangle using the `Fixed` class.
* **Concepts**:
    * **Barycentric Coordinates**: Using vector math to calculate relative positioning.
    * **Geometric Logic**: Applying fixed-point arithmetic to solve real-world coordinate problems.
    * High-level class composition and mathematical precision.

---

## 🚀 Technical Requirements
* **Standard**: C++ 98.
* **Compiler**: `c++` with `-Wall -Wextra -Werror` flags.
* **Precision**: The logic must handle the specific constraints of fixed-point math while avoiding the overhead of the `float` type where possible.

---
