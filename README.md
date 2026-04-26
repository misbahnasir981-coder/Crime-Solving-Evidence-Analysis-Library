Crime Solving & Evidence Analysis Library

Student Information

**Name:** Misbah Nasir
**Roll Number:** XXXXX

##Project Overview
This project is a custom C++ library designed to simulate the management and analysis of crime scene evidence. It applies object-oriented programming concepts to represent and evaluate different types of evidence used in investigations.

## Objective
The goal of this project is to demonstrate the use of:

* Function Overloading
* Operator Overloading
* Class Design and Encapsulation
within a real-world inspired problem domain.

## Features
* Create evidence records using multiple overloaded functions
* Combine and analyze evidence using overloaded operators (+, -)
* Compare evidence based on type and priority (==, <)
* Display structured output using << operator
* Modular design with separate library and main file
* 
##  Class Description
The project includes a class `Evidence` which stores:
* Evidence ID
* Type (DNA, Fingerprint, etc.)
* Weight (importance level)
* Priority (investigation level)

##  Project Structure
Crime-Solving-Evidence-Analysis-Library/
│
├── YourLibrary.h   // Class definition & implementation
├── main.cpp        // Demonstration of functionality
├── README.md       // Project documentation

##  Sample Output

--- Evidence 1 ---
ID: E01
Type: DNA
Weight: 5.5
Priority: 2

--- Evidence 2 ---
ID: E02
Type: Fingerprint
Weight: 3.0
Priority: 3

--- Combined Evidence ---
Type: DNA+Fingerprint
Weight: 8.5
Different Type
e1 has lower priority than e2

##Conclusion

This project demonstrates how C++ operator and function overloading can be used to model real-world systems like crime evidence analysis in a simple and effective way.
