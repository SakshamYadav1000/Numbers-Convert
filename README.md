// Number System Base Converter

A simple C++ program to convert numbers between different number systems: **Decimal**, **Binary**, **Octal**, and **Hexadecimal**.

---

// Features

- Convert Decimal to Binary, Octal, and Hexadecimal
- Convert Binary to Decimal, Octal, and Hexadecimal
- Convert Octal to Decimal, Binary, and Hexadecimal
- Convert Hexadecimal to Decimal, Binary, and Octal
- User-friendly console interface
- Re-runnable in a single session with option to repeat

---

// Technologies Used

- C++
- Basic I/O and Loops
- Character Arrays and Strings
- Math Library (`<math.h>`)
- String Manipulation

---

// Menu Options

When you run the program, you'll be prompted to select the input number system:

1. Decimal

2. Binary

3. Octal

4. Hexadecimal

After entering your number, the program will automatically convert and display results in the other number systems.

---

 // Example Usage

> SELECT YOUR NUMBER SYSTEM
  PRESS '1' For Decimal System
  PRESS '2' For Binary System
  PRESS '3' For Octal System
  PRESS '4' For Hexadecimal System
  YOUR CHOICE HERE: 1

  Enter Your Number In Decimal System [0-9]: 25

  Number In Binary System         : 11001
  Number In Octal System          : 31
  Number In Hexadecimal System    : 19

// Known Issues

Binary and Octal inputs are taken as integers, not strings (leading 0s are removed).

Hexadecimal inputs must be lowercase (a-f). Can be improved with better case-handling.

No error-checking for invalid inputs in non-decimal systems.

// Future Improvements

Add input validation for invalid digits

Allow case-insensitive hexadecimal input

Add GUI or web interface (optional)

Improve string handling for larger numbers

Created with ❤️ by Saksham.
Tech enthusiast & problem solver.
