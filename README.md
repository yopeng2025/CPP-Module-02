# CPP Module 02 Overview

This module contains a series of exercises designed to introduce fundamental concepts in C++ programming. Throughout the exercises, you'll learn about object-oriented programming, operator overloading, type conversion, and geometric algorithms.

## Exercises Overview
- **Exercise 00 (ex00)**: Introduction to class creation. Implement Orthodox Canonical Form (OCF) for a basic class.
- **Exercise 01 (ex01)**: Practice type conversion with constructor overloading and conversion operators.
- **Exercise 02 (ex02)**: Explore operator overloading by overloading arithmetic and relational operators.
- **Exercise 03 (ex03)**: Implement geometric algorithms, focusing on the BSP (Binary Space Partitioning) technique.

## Module Objectives
- Understand the significance of the Orthodox Canonical Form (OCF) in C++ classes, including the importance of copy constructors, assignment operators, and destructors.
- Gain hands-on experience with type conversions and learn when they are necessary.
- Implement operator overloading to enhance class usability and syntax intuitiveness.
- Explore geometric algorithms, particularly those applied in computer graphics and spatial data structures, such as BSP.

## Building Instructions
To build the exercises presented in this module, follow these steps:
1. Clone the repository from GitHub:
   ```bash
   git clone https://github.com/yopeng2025/CPP-Module-02.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CPP-Module-02
   ```
3. Compile the code using your preferred compiler, e.g., g++:
   ```bash
   g++ -o module02 *.cpp
   ```
4. Run the generated executable:
   ```bash
   ./module02
   ```

## Key Concepts
### Orthodox Canonical Form (OCF)
The Orthodox Canonical Form is a design pattern in C++ that ensures a class can manage its resources properly. It includes defining:
- A default constructor
- A copy constructor
- An assignment operator
- A destructor
This form promotes better resource management, especially when working with dynamic memory.

### Type Conversion
Type conversion involves converting one data type to another. C++ allows implicit and explicit conversions, and understanding these conversions is crucial for writing flexible and robust code.

### Operator Overloading
Operator overloading enables developers to define custom behavior for operators in user-defined types. By overloading operators, you can make your classes interact more intuitively with built-in data types.

### Geometric Algorithms (BSP)
Binary Space Partitioning (BSP) is a method used in computer graphics to recursively divide a space into convex subsets. BSP trees are commonly applied in rendering techniques and visibility calculations.

---
This module offers hands-on experience with essential C++ programming concepts through practical examples. We encourage you to experiment with the code and deepen your understanding of each topic covered in the exercises.  
