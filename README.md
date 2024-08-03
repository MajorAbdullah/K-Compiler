# K++ Compiler

## Overview
K-Compiler is a simple, educational compiler designed to demonstrate the basics of compiler construction. The project showcases fundamental concepts such as lexical analysis, parsing, syntax tree generation, and code generation, making it a valuable resource for students and educators in computer science.

## Features
1. **Lexical Analysis**: Converts source code into tokens.
2. **Parsing**: Generates a syntax tree from the tokens.
3. **Syntax Tree Generation**: Builds an abstract syntax tree (AST) to represent the program's structure.
4. **Code Generation**: Transforms the syntax tree into executable code.
5. **Error Handling**: Basic error detection and reporting during lexical analysis and parsing.

## Requirements
- Python 3.x
- Flex (Fast Lexical Analyzer Generator)
- Bison (Parser Generator)

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/MajorAbdullah/K-Compiler.git
    ```
2. Navigate to the project directory:
    ```bash
    cd K-Compiler
    ```
3. Install dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```
4. Run the compiler on a source code file:
    ```bash
    python k_compiler.py <source_code_file>
    ```

## Usage
Upon running the program, the K-Compiler will output the generated tokens, syntax tree, and executable code based on the provided source file. Follow the on-screen instructions to navigate through different options.

## File Structure
- `k_compiler.py`: Main compiler driver script.
- `lexer.l`: Lexical analyzer definition using Flex.
- `parser.y`: Parser definition using Bison.
- `ast.py`: Abstract Syntax Tree classes and definitions.
- `code_generator.py`: Code generation logic.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for review.

## Contact
For any queries or suggestions, feel free to reach out:
- **Email:** sa.abdullahshah.2001@gmail.com
- **LinkedIn:** [Syed Abdullah Shah](https://www.linkedin.com/in/syed-abdullah-shah-4018a5176)
