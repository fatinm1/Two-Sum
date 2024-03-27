# TwoSum Solution in C++

This repository contains a C++ solution to the classic "Two Sum" problem. The program finds two numbers in an array that add up to a specific target number and returns their indices.

## Problem Statement

Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`. You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.

## Solution Approach

The solution utilizes an unordered map (hash map) to store each number's value and its index as we iterate through the array. For each element, we calculate its complement by subtracting the current element's value from the target value. We then check if this complement exists in our hash map. If it does, we have found the two numbers that sum up to the target, and we return their indices.

### Features

- **Efficiency**: The solution runs in O(n) time complexity, making it efficient for large arrays.
- **Simplicity**: Utilizes a straightforward hashing strategy to find the solution.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC, Clang)
- Makefile or CMake (Optional, for building the project)

### Compiling the Program

Assuming you have saved the solution in a file named `sum.cpp`, you can compile it using g++:

```sh
g++ -o sum sum.cpp -std=c++11

Running the Program
After compilation, run the program using:
./sum

Note: This program is designed to be integrated into a larger project or tested with a specific driver code that calls the twoSum function.

Contributing
Contributions to enhance the solution, fix bugs, or improve the documentation are welcome. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -am 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a Pull Request.
License
This project is open-sourced under the MIT License. See the LICENSE file for more details.

Acknowledgments
Inspired by the Two Sum problem on LeetCode.
Thanks to everyone who has contributed to this project.
