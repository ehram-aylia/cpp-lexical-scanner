# C++ Lexical Scanner and Tokenizer

This project demonstrates how a compiler performs lexical analysis on C++ source code.

## Features
- Scanner using two-pointer technique for efficient token detection.
- Regex-based alternative tokenizer.
- Recognizes keywords, identifiers, numbers (int & float), operators, separators, and string literals.
- Handles multi-line comments and logs lexical errors.
- Sample input and output included (`input.txt` and `tokens.txt`).

## How it Works
1. Reads source code into memory.
2. Scans text to identify tokens.
3. Logs errors for unrecognized symbols.
4. Outputs a structured list of tokens and errors.
