# Calculator

A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
Must have python3 installed.

Execute run.sh,
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.
## Tests
You must have pytest installed and the sccm-4910 virtual environment
(I believe this is just a normal python virtual environment you can create, and just
pip install pytest).

activate the virtual environment with ```source path/to/venv/bin/activate```

run ./check.sh

Expected result is that all tests pass and exit code is 0.
## Stopping the program
Can stop the program by closing the terminal, or pressing Ctrl+C.
