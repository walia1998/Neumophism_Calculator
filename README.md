# Neumorphism Calculator (Dark/Light Mode)

## Overview
This is a simple **Neumorphism-style Calculator** that supports basic arithmetic operations and includes a **dark/light mode toggle**. It is built using **HTML, CSS, and JavaScript**.

## Features
- **Basic Arithmetic Operations:** Addition, Subtraction, Multiplication, Division.
- **Percentage (%) Calculation:** Converts a number to its percentage form.
- **Clear Button:** Resets the input field.
- **Dark/Light Mode Toggle:** Switch between dark and light themes using a toggle button.
- **Neumorphism Design:** Soft UI design for a modern and visually appealing look.

## Technologies Used
- **HTML** - For the structure of the calculator.
- **CSS** - For styling the calculator with a neumorphism effect.
- **JavaScript** - For handling user input and performing calculations.

## File Structure
```
Neumorphism-Calculator/
│── index.html        # Main HTML file
│── index.css         # Styling (Neumorphism effect)
│── index.js          # JavaScript logic
│── README.md         # Project documentation
```

## How to Use
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/walia1998/Neumophism_Calculator/tree/main
   ```
2. **Open the `index.html` file in a browser.**
3. Click the buttons to perform calculations.
4. Click the `Clear` button to reset the input.
5. Click `%` to convert a number to its percentage.
6. Click the `toggle button` to switch between light and dark modes.

## Code Explanation
### HTML (`index.html`)
- Contains a `<div>` with a `buttons` section for number and operator buttons.
- A `<h2>` element is used to display the result.
- Includes a `<div>` for the **toggle button** to switch between dark and light modes.

### CSS (`index.css`)
- Implements **Neumorphism design** using `box-shadow` for a soft UI effect.
- Styles the calculator layout, button effects, and dark/light mode.
- Uses `grid` layout for button arrangement.

### JavaScript (`index.js`)
- **Handles button clicks** to update the calculator display.
- **Evaluates expressions** when `=` is pressed.
- **Clears the display** when `Clear` is pressed.
- **Computes percentages** by dividing the current number by `100`.
- **Toggles dark mode** by adding/removing a CSS class to the `<body>` element.

## Example Usage
### Addition
```
5 + 3 = 8
```
### Percentage Calculation
```
50% = 0.5
```

## Future Improvements
- **Keyboard Support** for input.
- **Scientific Calculator Mode** for advanced functions.
- **Memory Functions** (M+, M-, MR) for storing calculations.

## License
This project is **open-source** and free to use.

---
Developed with ❤️ by Ashish Walia

