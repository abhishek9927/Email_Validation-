# 📧 Email Validation Script (Python)

This is a simple **Email Validation Program** written in Python.  
It checks whether a given email address follows basic formatting rules and prints whether it is valid or invalid.

## 🚀 Features
- Checks **minimum email length** (at least 6 characters)
- Ensures **first character is a letter**
- Validates that **only one `@` symbol** is present
- Checks for a valid **domain extension** (e.g., `.com`, `.net`, `.org`)
- Restricts **invalid special characters**
- Detects **spaces or uppercase letters** in the email

## 🛠 How It Works
1. **Takes email input** from the user
2. Validates the following:
   - Length of email (≥ 6)
   - Starts with a letter
   - Contains exactly one `@`
   - Ends with `.xyz` or `.xy` format
   - Contains only allowed characters (`a-z`, `0-9`, `_`, `.`, `@`)
   - No spaces, no uppercase letters, no special characters
3. Prints `"Right Email"` or `"Wrong Email"` based on the checks.

## 📂 Project Structure
