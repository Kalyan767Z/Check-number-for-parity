## Instructions for Running the Program

1. Open **Visual Studio** or any C# IDE of your choice.
2. Copy and paste the code from the provided source file into the IDE.
3. Compile and run the program.
4. Follow the on-screen prompt to input a number.

## Tasks Performed by the Program

- The program prompts the user for a number.
- It checks whether the number is even or odd.
- It validates the input to ensure it is a valid number.
- Displays the result based on the parity of the number.

## Description of the Program

This program allows the user to input a number, then checks if the number is even or odd. If the input is not a valid number, the program outputs an error message. The program uses simple logic to check if a number is divisible by 2 and determines its parity.

### Key Aspects:

- **Validation**: Uses `double.TryParse` to ensure input correctness.
- **Parity Check**: Checks if the number is even or odd using the modulus operator (`%`).
- **Error Handling**: Displays an error message if the input is invalid.

## Features of the Program

### Step-by-Step Explanation:

1. The user is prompted to input a number.
2. The input is validated using `double.TryParse` to ensure it is a valid numeric input.
3. If the input is valid, the program checks if the number is even or odd using the modulus operator (`%`).
4. Based on the result, the program outputs whether the number is "even" or "odd".
5. If the input is not valid, the program displays "Wrong number".

### Functions Overview:

- **`Main()`**:
  - Handles user input and validates it.
  - Checks if the number is even or odd using the modulus operator.
  - Displays the appropriate message based on the result.

## Program Logic Summary

This program allows users to easily check if a given number is even or odd. It provides clear error handling for invalid inputs and uses simple conditional logic to determine the result. The program is structured for readability and ease of use.
"""
