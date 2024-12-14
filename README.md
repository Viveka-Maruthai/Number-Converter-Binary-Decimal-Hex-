# Number Converter (Binary, Decimal, Hexadecimal)

This is a simple **Number Converter** web app that allows users to convert numbers between **Binary**, **Decimal**, and **Hexadecimal** formats. The app provides an input field where users can enter a number, and buttons to convert it into the respective formats.

## Features

- Convert a number between **Binary**, **Decimal**, and **Hexadecimal**.
- Display results in real-time after the conversion.
- Error handling for invalid inputs (e.g., non-numeric values).
- Simple, clean, and responsive user interface.

## Technologies Used

- **HTML**: Structure and layout of the page.
- **CSS**: Styling to enhance the look and feel of the app.
- **JavaScript**: Logic to handle number conversions between Binary, Decimal, and Hexadecimal formats.

## How to Use

1. Open the app in a web browser.
2. Enter a number in the input field.
3. Click one of the buttons to convert the number to **Binary**, **Decimal**, or **Hexadecimal**.
4. The converted result will be displayed below the buttons in the **Result** section.
5. If you enter an invalid value (non-numeric), an error message will be shown asking for a valid number.

## Example

- **Input:** `10`
- **Binary:** `1010`
- **Decimal:** `10`
- **Hexadecimal:** `A`

## Code Explanation

- The **HTML** structure includes:
  - A text input for entering the number.
  - Three buttons to trigger conversion to Binary, Decimal, and Hexadecimal.
  - A `div` element to display the result.

- The **CSS** provides basic styling to center the elements, style the buttons, input field, and display results.

- The **JavaScript** includes:
  - Functions to handle conversion to **Binary**, **Decimal**, and **Hexadecimal**:
    - `convertToBinary()`: Converts the input number to Binary.
    - `convertToDecimal()`: Converts the input Binary number to Decimal.
    - `convertToHex()`: Converts the input number to Hexadecimal.
  - Error handling to display a message if the input is invalid.
  - Real-time result display based on user input.
