# P01
Coding Project
Here's a README file that explains how to use the `convert_base` code.


# Base Conversion Program

This Python program allows you to convert a number from one base (between 2 and 16) to another base (also between 2 and 16). The program takes a number as input along with its original base and target base, then outputs the number converted to the target base.

## How It Works

The `convert_base` function handles the conversion by:
1. Converting the input number from its original base to a decimal (base 10) integer.
2. Converting the decimal integer to the target base and returning the result as a string.

### Code Breakdown
1. **Input**: The user inputs a number and its base (`b_num`), followed by the base they wish to convert to (`b_tar`).
2. **Decimal Conversion**: The program converts the input number to a decimal.
3. **Target Base Conversion**: The decimal number is converted to the target base using a list of digits, which are then reversed to form the final result.

### Usage

1. **Run the Program**: Run the code file in a Python environment.
2. **User Input**:
   - Enter the number to convert.
   - Specify the base of this number (must be between 2 and 16).
   - Specify the target base for the conversion (must also be between 2 and 16).
3. **Output**: The program will output the converted number in the target base.

### Example


Enter the number: A2
Enter the base of the number (2-16): 16
Enter the target base (2-16): 10
Converted number: 162
```

In this example, the hexadecimal number `A2` is converted to its decimal form `162`.

