![Luhn Algorithm Banner](https://github.com/martforge/Luhn-Algorithm/blob/main/images/luhn-algorithm-banner.jpg)

# Luhn Algorithm

A Python implementation of the **Luhn Algorithm**, which is a simple checksum formula used to validate various identification numbers, such as credit card numbers. This project was part of the **Scientific Computing with Python** course from [FreeCodeCamp](https://www.freecodecamp.org/), specifically the *Validate a Credit Card Number* project.

## Description

The **Luhn Algorithm** is a simple checksum formula used to validate a variety of identification numbers. It works by checking if the sum of the digits in the number, when processed with specific steps, is divisible by 10. This algorithm is widely used in validating credit card numbers, social security numbers, and other identification numbers.

This project implements the Luhn Algorithm and provides functions for validating and checking the correctness of such numbers.

## Features
- **Validation**: Checks if a given number (such as a credit card number) is valid using the Luhn Algorithm.
- **Checksum Calculation**: Calculates the checksum for a given number.
- Handles both **integer** and **string** inputs, while ignoring non-numeric characters.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/martforge/Luhn-Algorithm.git
