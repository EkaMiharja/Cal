# Cal - Simple Calculator

A simple and functional calculator web application built with HTML, CSS, and JavaScript. This project is designed for beginners who are learning web development fundamentals.

## Purpose

This project serves as a learning resource for beginners who want to understand:
- Basic HTML structure and form elements
- CSS styling and layout techniques
- JavaScript DOM manipulation
- Event handling in JavaScript
- Building interactive web applications

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Decimal number support
- Clear display function
- Error handling for invalid expressions
- Responsive and user-friendly interface
- Modern dark theme design

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Google Fonts (Poppins)

## Project Structure

```
Cal/
├── index.html      # Main HTML structure
├── styles.css      # Styling and layout
├── index.js        # Calculator functionality
└── README.md       # Project documentation
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/EkaMiharja/Cal.git
```

2. Navigate to the project directory:
```bash
cd Cal
```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server

## Usage

1. Click on number buttons to input numbers
2. Click on operator buttons (+, -, x, /) to perform operations
3. Click the "=" button to calculate the result
4. Click the "C" button to clear the display
5. Use the "." button for decimal numbers

## Learning Objectives

By studying this project, beginners will learn:

### HTML
- How to structure a calculator interface
- Using semantic HTML elements
- Linking external CSS and JavaScript files
- Implementing inline event handlers

### CSS
- Creating centered layouts with Flexbox
- Grid layout for button arrangement
- Styling form inputs and buttons
- Creating hover and active states
- Working with HSL color values
- Implementing rounded corners and modern UI design
- Using custom fonts from Google Fonts

### JavaScript
- DOM manipulation with `getElementById`
- Creating and using functions
- String concatenation for display updates
- Using `eval()` for expression evaluation (Note: In production, use a safer parsing method)
- Error handling with try-catch blocks
- Event handling through onclick attributes

## Code Explanation

### Key Functions

- `appendToDisplay(input)`: Adds the clicked number or operator to the display
- `clearDisplay()`: Clears the display field
- `calculate()`: Evaluates the mathematical expression and displays the result

### Note on eval()

This project uses `eval()` for simplicity in learning. In production applications, it is recommended to use safer alternatives like a custom parser or math.js library to avoid security vulnerabilities.

## Future Enhancements

Beginners can extend this project by:
- Adding keyboard support
- Implementing backspace/delete functionality
- Adding memory functions (M+, M-, MR, MC)
- Including scientific calculator features
- Adding calculation history
- Implementing themes (light/dark mode toggle)
- Making it fully responsive for mobile devices
- Replacing `eval()` with a safer expression parser

## Contributing

This is a learning project. Feel free to fork it and experiment with your own modifications.

## License

This project is open source and available for educational purposes.

## Author

EkaMiharja

## Acknowledgments

This project was created as a learning tool for web development beginners to understand the fundamentals of building interactive web applications.