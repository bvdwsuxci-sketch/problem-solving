🔢 Fibonacci Sequence Generator
An interactive C++ console application that generates and formats the famous Fibonacci Sequence up to a user-defined position (). The program handles large numerical values safely using extended integer types and structures the output inside a clean, readable array format.
🛠️ Development Tools
This project was built and managed using:
VS Code: The text editor used for writing and formatting the source code.
GCC / MinGW Compiler: Used to compile the C++ code into an executable program.
Git & GitHub: Used for local version control and cloud repository hosting.
Key Features
Array-Style Formatting: Outputs the sequence inside stylized brackets [0, 1, 1, 2, ...] for an elegant CLI presentation.
Large Number Support: Utilizes long long data types to prevent integer overflow as the sequence grows exponentially.
Basic Input Validation: Built-in guard clauses to intercept invalid positions () and gracefully output an error message.
Technical Breakdown
The Fibonacci Logic
The Fibonacci sequence is a mathematical series where each number is the sum of the two preceding ones, usually starting with  and . The mathematical recurrence relation is defined as:
With seed values:
Algorithmic Efficiency
Instead of using heavy recursion which can slow down the system (with a time complexity of $O(2^n)$), this implementation uses an Iterative Approach with a loop. It dynamically swaps three variables (a, b, and c) to calculate the next terms in linear time ( complexity), making it highly optimized and fast.
Credits
Conceptualized, structured, and developed by Zyad.
License
This project is open-source and available under the MIT License.
