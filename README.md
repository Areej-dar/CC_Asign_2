# Regex and AST Parsing Script

This Python project demonstrates the use of **regular expressions (regex)** and **Abstract Syntax Trees (AST)** for basic string analysis and code parsing.

## 📚 Features

1. **Regular Expressions (Regex) Analysis**:
   - Uses `re.findall()` to extract all word characters (`\w`) from the input string.
   - Uses `re.split()` to split the input string based on word characters.

2. **AST (Abstract Syntax Tree) Parsing**:
   - Parses a Python code snippet using the `ast` module.
   - Dumps the AST structure of the code snippet and executes it using `exec()`.

## 💻 How to Run

Make sure you have Python installed. Save the script as `regex_ast_script.py` and run it:

```bash
python regex_ast_script.py
🛠️ Technologies Used
Python: Core programming language.
re (Regex): For pattern matching and string analysis.
ast (Abstract Syntax Tree): For parsing and executing Python code.
