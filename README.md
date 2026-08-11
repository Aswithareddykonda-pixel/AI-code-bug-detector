# 🐞 AI Code Bug Detector

AI Code Bug Detector is a Python-based application that analyzes
source code and identifies common programming bugs.

The project uses Python Abstract Syntax Tree (AST) analysis to
detect potential errors and provides explanations and suggested fixes.

## Features

- Syntax error detection
- Undefined variable detection
- Division by zero detection
- Mutable default argument detection
- Empty exception handler detection
- Dangerous eval() detection
- Bug explanations
- Suggested solutions
- Simple Streamlit interface

## Technologies

- Python
- AST
- Streamlit
- Regular Expressions
- Git
- GitHub

## Project Structure

AI-Code-Bug-Detector/

├── app.py

├── bug_detector.py

├── requirements.txt

├── README.md

├── test_code/

│   └── sample_bug.py

└── screenshots/

    └── result.png

## Installation

Clone the repository:

git clone https://github.com/yourusername/AI-Code-Bug-Detector.git

Go to the project directory:

cd AI-Code-Bug-Detector

Install dependencies:

pip install -r requirements.txt

## Run

Run the application using:

streamlit run app.py

Then open the Streamlit URL in your browser.

## Example

Input:

def calculate(a, b=[]):
    result = a / 0
    print(total)
    return result

Output:

- Mutable Default Argument
- Division By Zero
- Undefined Variable

The system provides an explanation and suggested fix for each
detected issue.

## Applications

- Programming education
- Automated code review
- Debugging assistance
- Secure coding
- Developer productivity

## Limitations

The current version focuses on common Python code patterns.
It may not detect complex logical errors or bugs involving
external systems.

## Future Improvements

- Machine learning-based bug classification
- Large Language Model integration
- Automatic code correction
- Multi-language support
- GitHub repository analysis
- VS Code extension
- Security vulnerability detection
- Code quality scoring

## Result

The system successfully identifies several common Python
programming errors and provides understandable explanations
and recommendations.

## Author

Developed as an AI/Data Science academic project.

## License

This project is intended for educational purposes.
