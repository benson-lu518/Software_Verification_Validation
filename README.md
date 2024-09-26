# CSE-565 Project 3: Graphical User Interface Testing Project

## Table of Contents
1. [GUI Introduction](#1-gui-introduction)
   - [a. Version 1](#a-version-1)
   - [b. Version 2](#b-version-2)
   - [c. Test Coverage Reports](#c-test-coverage-reports)
2. [Tools](#2-tools)
   - [a. Programming Language](#a-programming-language)
   - [b. Package for GUI](#b-package-for-gui)
   - [c. Package for Testing](#c-package-for-testing)
3. [Test Cases and Results](#3-test-cases-and-results)
   - [a. Version 1](#a-version-1)
   - [b. Version 2](#b-version-2)
4. [Assessment of the Tools](#4-assessment-of-the-tools)
   - [a. Tkinter](#a-tkinter)
   - [b. Unittest](#b-unittest)
5. [References](#5-references)

## 1. GUI Introduction

### a. Version 1
This version of the project is a basic 'First round interview' GUI interface of size `600x600` pixels. The application includes:

- A title at the top indicating "First round interview".
- An ASU image in the middle.
- A 'Submit' button at the bottom.
- A scrollbar on the left.
- Three pages: 'Basic Information', 'Education', and 'Work Experience'.

#### Pages:
- **Basic Information**: Name and gender input.
- **Education**: School name and degree selection.
- **Work Experience**: Company name input and experience slider.

Once information is filled, you can press the 'Submit' button to send data to the backend.

### b. Version 2
In Version 2, the following modifications were made:

- Changed height to `500 pixels`.
- Changed width to `500 pixels`.
- Added a 'Title' combobox on the 'Work Experience' page.

### c. Test Coverage Reports
- **Statement coverage**: 100%
- **Decision coverage**: 93%

## 2. Tools

### a. Programming Language
- **Python**: The primary programming language used for this project due to its ease of use and comprehensive libraries.

### b. Package for GUI
- **Tkinter**: Python's standard GUI toolkit.

### c. Package for Testing
- **Unittest**: Used for testing the application.

## 3. Test Cases and Results

### a. Version 1 Test Cases
1. Number of elements on the 'Work Experience' page: **Pass**
2. Screen height equals `600 pixels`: **Pass**
3. Screen width equals `600 pixels`: **Pass**

### b. Version 2 Test Cases
1. Number of elements on the 'Work Experience' page: **Fail** 
2. Screen height equals `600 pixels`: **Fail**
3. Screen width equals `600 pixels`: **Fail**
4. Number of elements on the 'Work Experience' page equals `6`: **Pass**
5. Screen height equals `500 pixels`: **Pass**
6. Screen width equals `500 pixels`: **Pass**

## 4. Assessment of the Tools

### a. Tkinter
- **Ease of Use**: Simple to install and use.
- **Features**: Similar functionality to HTML/JavaScript, with detailed documentation.
- **Evaluation**: An effective tool for developing GUI applications in Python.

### b. Unittest
- **Usage**: Widely used in Python projects for testing.
- **Evaluation**: While powerful, sometimes synchronization issues arise in VSCode, requiring a restart.

## 5. References
- [Python Unittest](https://docs.python.org/3/library/unittest.html)
- [Tkinter GUI Documentation](https://docs.python.org/3/library/tkinter.html)
- [Tkinter GUI Layout](https://www.pythonguis.com/tutorials/use-tkinter-to-design-gui-layout/)

---

# CSE-565 Project 2: Structural-Based Testing

## Table of Contents
1. [Tool and Code Coverage](#1-tool-and-code-coverage)
2. [Test Cases](#2-test-cases)
3. [Test Coverage Reports](#3-test-coverage-reports)
4. [Static Analysis Tool](#4-static-analysis-tool)
5. [Assessment of the Tool](#5-assessment-of-the-tool)

## 1. Tool and Code Coverage
- **IDE**: Eclipse IDE was used to run the Java code.
- **Test Framework**: JUnit was used to create and execute the test cases.
- **Coverage Tool**: EclEmma was used to generate coverage reports.

## 2. Test Cases
1. Test Case 1: Cost > Input.
2. Test Case 2: Cost < Input.
3. Test Case 3: Cost = Input.
4. Test Case 4: Additional item buying logic with Cost > Input.

## 3. Test Coverage Reports
- **Statement Coverage**: 100%
- **Decision Coverage**: 93%

## 4. Static Analysis Tool
- **Tool**: SonarLint was used for static code analysis.
- **Impact Levels**: Issues detected are classified into high, medium, or low impact.

## 5. Assessment of the Tool
- **Usage**: SonarLint is widely used for various programming languages.
- **Evaluation**: It provides a simple installation process, with detailed reports on code quality and static analysis.

---

# CSE-565 Project 1: Specification-Based Testing & Design of Experiments

## Table of Contents
1. [Explanation of Test Cases](#1-explanation-of-test-cases)
2. [Assessment of the Test Cases](#2-assessment-of-the-test-cases)
3. [Assessment of the Tool](#3-assessment-of-the-tool)

## 1. Explanation of Test Cases
The project used **Design of Experiments (DOE)**, creating 25 cases from JMP.
The test cases achieved reasonable coverage, consisting of all possible factor combinations.

## 2. Assessment of the Test Cases
The maximum number of combinations was `800 (5*2*4*4*5)`, but DOE Pairwise Combinations reduced the number to 25, which still achieved sufficient code coverage.

## 3. Assessment of the Tool
- **Tool**: JMP was used to create the test cases.
- **Usage**: JMP is user-friendly and can easily handle complex data challenges.
- **Evaluation**: JMP is widely used across industries, and the software is easy to install from ASU's app page or the official website.

## References
- [JMP Official Website](https://www.jmp.com/zh_tw/home.html)
