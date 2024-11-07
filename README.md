# Hands-on Lab: Exploring Watsonx Code Assistant with Python and GoLang

## Objective
In this lab, you'll explore the capabilities of IBM Watsonx Code Assistant for generating, explaining, and improving code. You’ll choose one language—**Python** or **GoLang**—and work through the commands provided in the instructions to see how Watsonx Code Assistant can help with common programming tasks.

## Getting Started

1. **Choose Your Language**:
   - Decide if you want to work with **Python** or **GoLang**.
   - In the file structure, find the corresponding folder for your chosen language (either `/python` or `/golang`).
   - The folder contains two files: `bad.py` (or `bad.go`) and `sample.py` (or `sample.go`), which you will use for this lab.

2. **Try Out Each Instruction with Watsonx Code Assistant**:
   - Open the relevant file (`bad.py` or `bad.go`) in Visual Studio Code (VS Code).
   - Use Watsonx Code Assistant to try out each of the commands in the **Instructions** section.
   - As you complete each command, document the results, changes, or improvements you observe.

## Instructions and Commands to Try

### 1. **Please explain the code for @filename**
   - Use Watsonx Code Assistant to generate an explanation for the entire code in `@filename`.
   - Document the overall purpose and functionality of the code.

### 2. **Then let explain each function**
   - Ask Watsonx Code Assistant to generate explanations for each function within the file.
   - Note the purpose of each function, its parameters, and its return values.

### 3. **Generate Python/GoLang docstrings for the code provided: `@filename`**
   - Use Watsonx Code Assistant to generate detailed docstrings for each function in the code.
   - Ensure the docstrings follow the conventions of your chosen language (e.g., PEP 257 for Python).

### 4. **Give some technical specification, recommend how to change code in `@filename` to satisfy a requirement**
   - Review the code and identify potential improvements or optimizations.
   - Use Watsonx Code Assistant to generate a technical specification that includes recommendations for modifications.

### 5. **Please fix this code: `@bad.py` or `@bad.go`**
   - Open `bad.py` or `bad.go` in your chosen language.
   - Ask Watsonx Code Assistant to identify issues in the code and suggest fixes.
   - Implement and document the improvements.

### 6. **Using `/docs IBM give code …`**
   - If applicable, explore any IBM-provided documentation to improve or enhance the code functionality.

### 7. **Refactor this larger chunk of code into smaller functions `@filename`**
   - Select a larger block of code within `@filename`.
   - Use Watsonx Code Assistant to refactor it into smaller, modular functions for readability and maintainability.

### 8. **Generate Test Cases for `@filename`**
   - Generate test cases for each function using Watsonx Code Assistant.
   - If working in Python, use `unittest` or `pytest`. If in GoLang, use Go’s `testing` package.
   - Ensure each function has at least one corresponding test case.

### 9. **Generate Build and Deployment (Dockerfile) Script for the Code**
   - Use Watsonx Code Assistant to create a Dockerfile for the code in `@filename`.
   - This Dockerfile should include all necessary instructions to build and deploy the application.

## Final Steps

1. **Document Your Observations**:
   - For each command, take notes on how Watsonx Code Assistant helped, any issues encountered, and the final output.

2. **Summarize Improvements**:
   - Summarize the key improvements Watsonx Code Assistant made to the code, such as enhanced readability, modularity, error handling, and documentation.

---

### Example Output Documentation

After each step, you can add documentation like:

```markdown
### Step 1: Explain the Code for `sample.py`

Watsonx Code Assistant provided a clear explanation of `sample.py`, describing its purpose as generating and processing complex objects. Each function was outlined, and Watsonx also highlighted how the code flows from data generation to processing and output.

### Step 5: Fixing the Code in `bad.py`

Using Watsonx Code Assistant, the errors in `bad.py` were identified, particularly the missing variable and syntax issues. After implementing the fixes, the code ran successfully without errors.