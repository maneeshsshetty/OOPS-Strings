# Python String Exercises

![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

This repository contains a collection of **20 Python scripts** designed to practice and master string manipulation. Each script (`question1.py` to `question20.py`) solves a specific problem, ranging from basic operations to more complex logic involving `itertools` and data formatting.

## 📖 Table of Contents

- [Project Structure](#-project-structure)
- [Key Highlights & Examples](#-key-highlights--examples)
- [Prerequisites](#-prerequisites)
- [How to Run](#-how-to-run)
- [Topics Covered](#-topics-covered)

## 📂 Project Structure

Here is a quick reference guide to the exercises included in this repository:

| File | Challenge / Description | Key Concepts |
|------|-------------------------|--------------|
| `question1.py` | Calculate string length without `len()` | Loops, Counters |
| `question2.py` | Count character frequency | Dictionaries |
| `question3.py` | Create a string from first 2 & last 2 chars | Slicing |
| `question4.py` | Replace first char occurrences with `$` | String Manipulation |
| `question5.py` | Swap first two chars of two strings | Concatenation, Slicing |
| `question6.py` | Add 'ing' or 'ly' suffix | Conditionals |
| `question7.py` | Replace 'not...poor' with 'good' | `find()`, Substrings |
| `question8.py` | Find length of the longest word | Lists, `max()` |
| `question9.py` | Remove character at index `n` | Indexing |
| `question10.py` | Sort unique words from comma-separated list | `set()`, `sorted()`, `split()` |
| `question11.py` | Context-aware uppercase conversion | String Methods |
| `question12.py` | Reverse string if length is multiple of 4 | Logic, Reversing |
| `question13.py` | Check start of string | `startswith()` |
| `question14.py` | Number formatting (Currency/Decimal) | f-strings, format |
| `question15.py` | Count repeated chars | `collections`, `defaultdict` |
| `question16.py` | Print character index | `enumerate()` |
| `question17.py` | Convert string to list | Type Casting |
| `question18.py` | Swap commas and dots | `maketrans()`, `translate()` |
| `question19.py` | Find smallest and largest words | Loops, Comparison |
| `question20.py` | Remove consecutive duplicates | `itertools.groupby` |

## 🌟 Key Highlights & Examples

Here are a few examples of what these scripts can do:

### 1. Advanced String Replacement (`question7.py`)
Replaces a substring starting with 'not' and ending with 'poor' with 'good'.
```python
Input:  'The lyrics is not that poor!'
Output: 'The lyrics is good!'
```

### 2. Removing Consecutive Duplicates (`question20.py`)
Collapses consecutive duplicate characters into a single character.
```python
Input:  'aabcdaee'
Output: 'abcdae'
```

### 3. Formatting Numbers (`question18.py`)
Swaps commas and dots, useful for converting between currency formats (e.g., Euro to US).
```python
Input:  '32.054,23'
Output: '32,054.23'
```

## 🛠 Prerequisites

- **Python 3.x**: Ensure you have Python installed. You can check by running:
  ```bash
  python --version
  ```

## 🚀 How to Run

1.  **Clone the repository** or download the files to your local machine.
2.  Open your terminal or command prompt.
3.  Navigate to the directory containing the files.
4.  Run a specific script using:

    ```bash
    python question1.py
    ```
    *(Replace `question1.py` with the file you wish to run)*

## 📚 Topics Covered

- **String Traversal & Slicing**: Accessing and modifying parts of strings.
- **Built-in Methods**: Mastery of `find`, `replace`, `translate`, `split`, `join`, etc.
- **Data Structures**: Using `lists`, `dictionaries`, and `sets` for string processing.
- **Libraries**: Intro to standard libraries like `itertools` and `collections`.
- **Logic**: constructing algorithms to solve text-based problems.

---
*Happy Coding!*
