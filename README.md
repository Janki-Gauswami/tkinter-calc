### GUI Calculator in Python
This is a simple calculator application built using Python's tkinter module. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division through a graphical user interface (GUI).

## Features

Input field to enter numbers

Buttons for digits 0-9

Buttons for operations: +, -, *, /

= button to calculate and display result

Clear button to reset the input field

##  Requirements

Python 3.x installed on your system

##  How to Run

Clone or download this repository.

Open a terminal or command prompt.

Run the script using Python:

python calc.py

This will open a window with the calculator GUI.

## Project Structure

calc.py      # Main Python file containing the calculator code
README.md          # This file

## Code 

Entry Widget: Displays current input or result

Button Widgets: For numbers and operations

Functions:

click(num): Adds the number to the current input

add(), sub(), mul(), div(): Handle operation logic

equal(): Performs calculation based on the selected operation

clear(): Clears the input field (Note: Not yet connected)

## Notes

The clear button is created but currently not functional (missing command=clear). You can fix it by modifying its code:

b = Button(window, text ='clear', width = 12, command=clear)
Division by zero is not handled, and will throw an error.

## License

This project is for educational purposes and is open for modification and reuse.