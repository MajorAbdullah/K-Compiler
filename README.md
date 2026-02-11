# K++ Compiler
### A custom programming language compiler built from scratch in Python

K++ Compiler is an educational compiler project that implements a complete compilation pipeline for a custom-designed programming language called K++. Built entirely in a Jupyter Notebook, it walks through every phase of compilation -- from lexical analysis to target code generation -- making it an ideal learning resource for compiler design.

---

## Features

- **Custom Language Design** -- K++ defines its own keywords (`show`, `get`, `if`, `else`, `repeat`), data types (`num`, `point`, `abc`, `text`, `yesno`), operators, and syntax rules
- **Lexical Analyzer** -- Tokenizes K++ source code into classified tokens (keywords, data types, identifiers, operators, symbols, strings, numbers, comments) using regex-based pattern matching
- **Syntax and Semantic Analyzer** -- Recursive descent parser that validates program structure, enforces grammar rules, and performs type checking with detailed error reporting
- **Symbol Table Management** -- Tracks variable declarations, types, memory addresses, and scope information throughout the compilation process
- **Intermediate Code Generation (ICG)** -- Produces three-address code as an intermediate representation for further optimization
- **Code Optimization** -- Implements constant folding and dead code elimination passes on the intermediate representation
- **Target Code Generation** -- Converts optimized intermediate code into low-level assembly-like target instructions (`MOV`, `ADD`, `SUB`, `MUL`, `DIV`, `CMP`, `JMP`, `JE`, `JNE`)
- **Comprehensive Error Handling** -- Custom `ParseError` class with detailed messages showing expected vs. actual tokens and line context

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Regex](https://img.shields.io/badge/Regex-000000?style=for-the-badge&logo=regex&logoColor=white)

---

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MajorAbdullah/K-Compiler.git
   ```
2. Navigate to the project directory:
   ```bash
   cd K-Compiler
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook K++.ipynb
   ```

---

## Usage

The notebook is organized into clearly labeled sections. Run each cell sequentially to observe the compilation pipeline in action:

1. **Language Rules** -- Review the K++ language specification (keywords, data types, operators, symbols, comments, identifiers)
2. **Lexical Analyzer** -- Tokenize sample K++ programs and inspect the generated token stream
3. **Syntax and Semantic Analyzer** -- Parse token streams, build parse trees, and populate the symbol table
4. **Code Generator and Optimizer** -- Generate intermediate three-address code, apply optimizations, and produce target assembly-like instructions

### Example K++ Code

```
num my_integer = 10/
point my_float = 3.14/
text my_string = "Hello, world!"/
yesno my_boolean = true/

get my_input/
show my_input/

if my_boolean == yesno true
    show "The boolean is true"/
else
    show "The boolean is false"/

repeat 5 times
    show "Loop iteration"/
```

---

## Project Structure

```
K-Compiler/
|-- K++.ipynb          # Complete compiler implementation (Lexer, Parser, Symbol Table, ICG, Optimizer, Code Generator)
|-- README.md          # Project documentation
```

---

## Contributing

Contributions are welcome. Please fork this repository and submit a pull request for review. For major changes, open an issue first to discuss your proposed modifications.

---

## Contact

- **Email:** sa.abdullahshah.2001@gmail.com
- **LinkedIn:** [Syed Abdullah Shah](https://www.linkedin.com/in/syed-abdullah-shah-4018a5176)
