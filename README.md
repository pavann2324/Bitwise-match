# Bitwise Matching Pattern

This project provides a simple tool to find the next largest integer with the same number of binary `1`s as a given input integer. It uses bitwise operations to efficiently calculate the result.

## Features

- **User-Friendly Input**: Accepts a non-negative integer as input.
- **Efficient Algorithm**: Implements an optimized algorithm to find the next largest number with the same binary `1`s.
- **Clear Output**: Displays the result or relevant error messages if no valid result exists.

## Technologies Used

- **HTML5**: Provides the structure for the web interface.
- **CSS3**: Styles the interface for a clean and minimalistic look.
- **JavaScript**: Contains the core logic for processing the input and calculating the result.

## Usage

1. **Input the Number**:
   - Enter a non-negative integer in the input field. Example: `6`.

2. **Get the Result**:
   - Click the **Find Next Larger** button.
   - The application will display the next largest integer with the same number of binary `1`s or an appropriate error message.

3. **Examples**:
   - Input: `6` (Binary: `110`) → Output: `9` (Binary: `1001`).
   - Input: `1` (Binary: `1`) → Output: `2` (Binary: `10`).

## How It Works

1. **Algorithm**:
   - Count trailing zeros and consecutive ones in the binary representation.
   - Flip the rightmost non-trailing zero to `1`.
   - Clear all bits to the right of this flipped bit.
   - Add the appropriate number of `1`s to maintain the original count.

2. **Edge Cases**:
   - If the input is invalid (e.g., negative or non-integer), the tool shows an error.
   - If no valid result exists, an error message is displayed.

3. **Error Handling**:
   - Invalid input: Displays "Please enter a valid non-negative integer."
   - No larger number: Displays "No larger integer with the same number of binary 1s exists."

