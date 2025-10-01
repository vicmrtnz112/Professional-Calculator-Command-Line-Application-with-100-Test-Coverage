# Professional Calculator Command-Line Application with 100% Test Coverage

This is a modular, professional-grade command-line calculator application built in Python.  
It supports basic arithmetic operations, user-friendly commands, and robust error handling.

---

## Project Structure
Professional Calculator Command-Line Application with 100% Test Coverage/
│
├── app/
│ ├── calculation/ # Base Calculation class
│ ├── calculator/ # Main REPL interface
│ └── operation/ # Arithmetic operations (add, subtract, multiply, divide)
│
├── tests/
│ ├── test_calculation.py # Unit tests for calculation classes
│ ├── test_calculator.py # Unit tests for calculator REPL
│ └── test_operations.py # Unit tests for arithmetic operations
│
├── .github/workflows/ # CI workflow for GitHub Actions
├── main.py # Entry point to start the calculator
├── requirements.txt # Project dependencies
├── pytest.ini # Pytest configuration
├── .coveragerc # Coverage configuration
└── README.md # Project documentation

## Setup Instructions
1. Clone the repository
2. Create a virtual environment
3. Install Dependencies

## Running the Calculator
1. Start the calculator REPL by running:
    - python main.py
2. REPL Instructions:
    - Enter operations in the format: Enter operations in the format:
    - Supported operations: add, subtract, multiply, divide
    - Type exit to quit the calculator.

**Features:**
- REPL interface (continuous user input)
- Addition, subtraction, multiplication, division
- Special commands: `help`, `history`, `exit`
- Input validation and error handling (division by zero, invalid input, keyboard interrupts)
- Calculation history
- Modular design for maintainability
