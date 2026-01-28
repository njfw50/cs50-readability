# 📚 Readability - Text Analysis Tool

[![Language: C](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
This project is a command-line utility that computes the readability level of a given text using the **Coleman-Liau index**. It was developed as part of the Harvard CS50x curriculum to demonstrate proficiency in string manipulation, mathematical algorithms, and low-level memory management in C.

The Coleman-Liau index is designed to output the U.S. grade level that is needed to comprehend some text. The formula is:
`index = 0.0588 * L - 0.296 * S - 15.8`
Where **L** is the average number of letters per 100 words and **S** is the average number of sentences per 100 words.

## 🚀 Features
- **Accurate Parsing**: Efficiently counts letters, words, and sentences while handling punctuation and whitespace.
- **Mathematical Precision**: Implements rounding logic to provide the most accurate grade level.
- **Robust Input Handling**: Validates user input to ensure consistent results.

## 🛠️ Technical Skills Demonstrated
- **C Programming**: Use of standard libraries (`stdio.h`, `ctype.h`, `math.h`, `string.h`).
- **Algorithm Implementation**: Translating complex mathematical formulas into functional code.
- **Modular Design**: Code organized into helper functions for better readability and maintenance.

## 💻 Getting Started

### Prerequisites
- A C compiler (e.g., `gcc` or `clang`)

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/njfw50/cs50-readability.git
   cd cs50-readability
   ```
2. Compile the program:
   ```bash
   gcc readability.c -o readability -lm
   ```
3. Run the tool:
   ```bash
   ./readability
   ```

## 📖 Example
```text
Text: Congratulations! Today is your day. You're off to Great Places! You're off and away!
Grade 3
```

---
*Developed as part of Harvard's CS50x.*
