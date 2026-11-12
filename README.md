# Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.

## What it will do
Add, subtract, multiply and divide two numbers; display the result.

## How to run it
Run: python3 calculator.py or ./run.sh
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

## Tests
Activate the SCCM4910 environment using: source /opt/python-venv/sccm-4910/bin/activate>
Run: ./check.sh
5 tests should pass. One for each operation (+,-,*,/) and one edge case of uneven addition.
Run: echo $?
Exit status should be 0
