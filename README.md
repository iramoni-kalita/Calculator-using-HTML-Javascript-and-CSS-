# Simple Calculator Web Application

A clean, responsive calculator built with HTML, CSS, and JavaScript that runs in any modern web browser.

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Parentheses support for complex expressions
- Decimal point input
- Clear button to reset the calculator
- Error handling for invalid expressions
- Responsive design that works on mobile and desktop
- Visually appealing button styling with hover effects

## How to Use

1. Click the number buttons (0-9) to input numbers
2. Use the operator buttons (+, -, ×, /) for calculations
3. Use parentheses ( ) for complex expressions
4. Press "C" to clear the display
5. Press "=" to calculate the result

## Installation

No installation required! Simply open the `calculator.html` file in any web browser.

## Code Structure

- **HTML**: Defines the calculator structure with display and buttons
- **CSS**: Styles the calculator with a modern, clean look
- **JavaScript**: Handles the calculator logic:
  - `appendToDisplay()` - Adds characters to the display
  - `clearDisplay()` - Resets the calculator
  - `calculate()` - Evaluates the expression and shows result

## Limitations

- Uses JavaScript's `eval()` which has security implications in production (this is fine for a local demo)
- No memory functions or advanced operations
- Basic error handling (shows "Error" for invalid expressions)

## Screenshot

![Calculator Screenshot](screenshot.png) *(Note: You would need to add an actual screenshot file to your repository)*

## License

This project is open source and available under the MIT License.
