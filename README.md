# Modern Web Calculator

![Calculator Screenshot](./screenshot.png)

A sleek, responsive calculator web application with advanced functionality and keyboard support.

## Features

- **Basic Operations**: Addition, subtraction, multiplication, division
- **Advanced Functions**: 
  - Percentage calculations
  - Sign toggle (±)
  - Backspace (delete last digit)
  - Clear all (C)
- **User Experience**:
  - Calculation history display
  - Keyboard support
  - Responsive design
  - Interactive button feedback
- **Visual Design**:
  - Modern color scheme
  - Clean interface
  - Animated button effects

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6)
- Font Awesome icons

## Installation

No installation required! Simply open `index.html` in any modern web browser.

## Usage

1. **Basic Calculation**:
   - Click buttons or use keyboard to input numbers
   - Select an operation (+, -, ×, ÷)
   - Press equals (=) or Enter to calculate

2. **Special Functions**:
   - `C`: Clear all
   - `⇐`: Backspace (delete last digit)
   - `±`: Toggle positive/negative
   - `%`: Percentage calculation

3. **Keyboard Support**:
   - Numbers: 0-9
   - Operators: +, -, *, /
   - Enter: Calculate
   - Escape: Clear
   - Backspace: Delete last digit

## Project Structure
calculator/
├── index.html # Main HTML file
├── style.css # CSS styles
├── script.js # JavaScript functionality
└── README.md # Project documentation


## Customization

To change the color scheme, modify these CSS variables in `style.css`:

```css
:root {
  --primary-color: #6c5ce7;       /* Calculator body */
  --secondary-color: #a29bfe;     /* Operator buttons */
  --dark-color: #2d3436;          /* Number buttons */
  --light-color: #f5f6fa;         /* Text color */
  --danger-color: #d63031;        /* Clear button */
  --success-color: #00b894;       /* Equals button */
  --function-color: #636e72;      /* Special function buttons */
}