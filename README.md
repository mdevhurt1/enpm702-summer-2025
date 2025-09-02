# enpm702_summer_2025 (ARCHIVED)
Code for C++ lectures for ENPM702 (Summer 2025)

## Lecture 1: Course Overview
Simple main function to describe the build process of a C++ project.

## Lecture 2: Introduction to C++
- Variables
- Type Conversion

## Lecture 3: Normal Pointers
- Pointers
- References

## Lecture 4: STL Containers

### Learning Objectives

- Declare, initialize, and manipulate `std::string` objects using common methods for access, modification, concatenation, and insertion operations.
- Describe the internal memory model of `std::string`, including Small String Optimization (SSO), the relationship between size and capacity, and dynamic memory allocation strategies.
- Manage `std::string` memory usage efficiently using `reserve()`, `resize()`, and `shrink_to_fit()` methods.
- Compare and contrast C-style arrays with `std::array`, understanding compilation requirements and safety considerations.
- Declare, initialize, and manipulate both single and multidimensional arrays using proper syntax and access patterns.
- Understand the dynamic nature of `std::vector`, including its memory management, capacity growth strategies, and performance characteristics.
- Perform efficient insertion and deletion operations on vectors using `push_back()`, `emplace_back()`, `insert()`, `erase()`, and related methods.
- Apply best practices for memory management across all STL container types to write efficient and maintainable code.

## Lecture 5: Functions

### Learning Objectives

- Understand function fundamentals including benefits, declarations vs definitions, and file organization with headers.
- Master function mechanics including calls, parameter passing (by value, reference, pointer), and proper documentation practices.
- Implement advanced function features including static variables, return value handling, function overloading, and default parameters.
- Analyze program execution using stack frames and implement recursive functions with proper base cases.

## Lecture 6: Smart Pointers

### Learning Objectives

- Explain RAII principles and implement automatic resource management using smart pointers to prevent memory leaks and ensure exception safety.
- Analyze ownership semantics and select appropriate smart pointer types (`std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`) based on resource sharing requirements.
- Implement exclusive ownership patterns using `std::unique_ptr` with proper initialization, move semantics, and method usage (`get()`, `release()`, `reset()`, `swap()`).
- Design shared ownership systems using `std::shared_ptr` with reference counting, control blocks, and safe resource sharing across multiple objects.
- Apply `std::weak_ptr` to break circular dependencies and implement safe resource observation without affecting object lifetimes.
- Evaluate function parameter strategies (sink, reseat, return) and implement proper ownership transfer patterns in modern C++ applications.

## Reading Material
- Basic Types
- Operators
- Selection
- Iteration

## Version Control
- Git
- GitHub

## rwa2_enpm702_summer_2025

### Assignment Overview
This repository contains the starter code for Assignment #2 in ENPM702. Students will implement a **Dual-Sensor System** for an autonomous robot operating in a warehouse environment.

### Learning Objectives
- **Modern C++17 Features**: Structured bindings, range-based for loops, uniform initialization
- **STL Containers**: Advanced usage of vector, tuple, map, unordered_map
- **STL Algorithms**: std::accumulate and container operations
- **Const-correctness**: Proper use of const, constexpr, and immutable data patterns
- **Data Processing**: Statistical calculations, validation, and quality assessment
- **Professional Output**: Formatted console output and modern C++ practices

### System Description
The robot uses two sensor types:
- **LIDAR**: Measures distances to nearby objects for obstacle detection (8 readings per timestamp)
- **Camera**: Captures RGB color values for environment analysis and lighting classification

### Assignment Requirements
- **Implementation**: All logic must be within the `main()` function
- **C++17 Features**: Must demonstrate structured bindings, uniform initialization, const-correctness
- **Data Processing**: Generate 5 timestamps of sensor data, validate quality, calculate statistics
- **Modern Practices**: Use `'\n'` instead of `std::endl`, proper const usage, meaningful variable names

