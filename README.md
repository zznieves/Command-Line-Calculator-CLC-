# Command-Line-Calculator-CLC-

# Project 001: Command-Line Calculator
**Version:** 1.0  
**Language:** TypeScript  
**Interface:** Command-Line Interface (CLI)  
**Status:** Ready for Development

### 1. Problem Statement
Users need a simple way to perform basic arithmetic calculations without opening a graphical calculator application.

### 2. Objective
Develop a command-line calculator that accepts two numerical inputs and an arithmetic operator, performs the calculation, and displays the result.

The application must handle invalid inputs gracefully.

### 3. Target Users
Individuals who need to perform basic arithmetic operations through a terminal.

### 4. Functional Requirements

**FR-01: Arithmetic Operations**

The calculator must support:
- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)

**FR-02: Numerical Input**

The calculator must:
- Accept positive and negative numbers.
- Accept decimal numbers.
- Accept zero.
- Reject nonnumeric input.

**FR-03: Output**

The calculator must display the result of a successful calculation.

Example:

```text
Enter first number: 10
Enter operator: +
Enter second number: 5

Result: 15
```

**FR-04: Error Handling**

The calculator must handle:
- Division by zero.
- Unsupported operators.
- Invalid numerical input.
- Empty input.

Errors must produce understandable messages without terminating the application unexpectedly.

**FR-05: Repeated Calculations**

After displaying a result or error, the application must allow the user to perform another calculation or exit.

### 5. Nonfunctional Requirements
- The application must run using Node.js.
- Source code must be written in TypeScript.
- Calculation logic must be separated from terminal input/output.
- The code should be readable and maintainable.
- Calculations must not produce an unhandled exception.

### 6. Out of Scope — Version 1
The following features are explicitly excluded:
- Graphical user interface.
- Scientific calculations.
- Calculation history.
- Multiple simultaneous operators.
- User accounts or databases.
- Arbitrary-precision arithmetic.

### 7. Definition of Done
The project is complete when:
1. All four arithmetic operations work.
2. Positive, negative, decimal, and zero inputs are supported.
3. Invalid inputs generate appropriate errors.
4. Users can perform multiple calculations.
5. Users can exit the application.
6. All defined evaluation tests pass.
7. The project includes a README explaining installation and usage.