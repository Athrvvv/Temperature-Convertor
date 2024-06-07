# Temperature Converter

## Description

This is a simple yet elegant web application that allows users to convert temperatures between Celsius and Fahrenheit. The application is built using HTML, CSS, and JavaScript, and it features a responsive and modern design.

## Features

- **Real-time Conversion**: As you type a value into one of the input fields (Celsius or Fahrenheit), the corresponding temperature in the other unit is instantly calculated and displayed.
- **User-friendly Interface**: The application has a clean, professional design that ensures a great user experience.
- **Responsive Design**: The layout adjusts seamlessly to different screen sizes, making it usable on both desktop and mobile devices.
- **Input Validation**: The input fields accept decimal numbers, allowing for precise temperature conversions.

## Screenshot

![Temperature Converter Screenshot](screenshot.png)

## Live Demo

Check out the live demo [here](https://your-live-demo-link.com).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/temperature-converter.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd temperature-converter
    ```
3. **Open `index.html` in your preferred web browser**.

## Usage

1. Enter a temperature value in either the Celsius or Fahrenheit input field.
2. The equivalent temperature in the other unit will be automatically calculated and displayed.

## Code Overview

### HTML

The HTML file contains the structure of the temperature converter, including two input fields for Celsius and Fahrenheit, respectively.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Converter</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <center>
        <h1>Temperature Converter</h1>
        <form>
            <label for="cel">Enter temperature in Celsius:</label>
            <input type="number" step="any" placeholder="Enter temperature in Celsius" id="cel" /><br>
            <label for="far">Enter temperature in Fahrenheit:</label>
            <input type="number" step="any" placeholder="Enter temperature in Fahrenheit" id="far" />
        </form>
    </center>
    <script src="script.js"></script>
</body>
</html>
