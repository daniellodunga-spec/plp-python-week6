# Python Error Handling – Safe Functions

This assignment focuses on building resilient Python functions that gracefully handle unexpected errors using `try` and `except` blocks, ensuring programs run smoothly without crashing.

## Project Files

* **`safe_tools.py`**: A module containing utility functions for error-safe division, string-to-number conversion, and dictionary key lookups.
* **`unbreakable.py`**: A test script that imports and executes the utility functions to verify they produce the required output.
<img width="748" height="210" alt="wk6" src="https://github.com/user-attachments/assets/f2b5dd52-a720-4caa-afe1-61114f230b07" />

## Key Takeaway

An `if` statement can only check for conditions you explicitly anticipate before running code. In contrast, `try/except` blocks actively catch unexpected runtime errors—like attempting to convert invalid text into a number (`int("abc")`)—preventing the program from crashing.
