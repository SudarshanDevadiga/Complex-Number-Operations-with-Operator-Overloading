# Complex Number Operations with Operator Overloading

A C++ program demonstrating operator overloading for complex number arithmetic operations including addition and subtraction.

## Description

This program implements a Complex Number class with overloaded operators (+, -) to perform arithmetic operations on complex numbers. It showcases object-oriented programming concepts including operator overloading and class member functions.

### Key Features
- Complex number operations
- Operator overloading
- User input handling
- Formatted output display
- Object-oriented design

## Class Structure

```cpp
class complex {
private:
    int a, b;  // Real and Imaginary parts
public:
    void get_data();
    complex operator+(complex ob);
    complex operator-(complex ob);
    void display();
};
