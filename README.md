# 🚀 C Compiler Design - Built From Scratch

A comprehensive compiler implementation for the C programming language, designed and developed to understand the fundamental concepts of compiler construction. This project implements all major phases of compilation including lexical analysis, syntax parsing, semantic analysis, and code generation.

## 📋 Overview

This compiler project demonstrates the complete workflow of translating C source code into executable machine code. Built with a focus on understanding compiler theory and practical implementation, it covers:

- **Lexical Analysis**: Tokenization of C source code
- **Syntax Analysis**: Parse tree generation using Yacc/Bison
- **Semantic Analysis**: Type checking and symbol table management
- **Code Generation**: Target code generation

## 🛠️ Technologies Used

- **Flex/Lex**: For lexical analysis
- **Yacc/Bison**: For syntax analysis and parsing
- **C++**: Core implementation language
- **Windows**: Development and testing environment

## 📁 Project Structure

```
├── Exercise 1.cpp          # Lexical analyzer exercises
├── Exercise 2.cpp          # Parser exercises
├── Final/
│   ├── lexer.l            # Flex specification for tokenization
│   ├── parser.y           # Yacc grammar rules
│   ├── parser2.y          # Enhanced parser version
│   ├── lex.cpp            # Generated lexical analyzer
│   └── Other Parsers/     # Alternative parser implementations
├── LICENSE                # Apache 2.0 License
└── README.md             # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Flex (Fast Lexical Analyzer Generator)
- Bison/Yacc (Parser Generator)
- C++ Compiler (GCC/MSVC)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/darkphoenix2208/C_Compiler_DESIGNING_FROM_SCRATCH.git
   cd C_Compiler_DESIGNING_FROM_SCRATCH
   ```

2. **Compile the lexer**
   ```bash
   flex -o lex.cpp Final/lexer.l
   ```

3. **Compile the parser**
   ```bash
   bison -d Final/parser.y
   ```

4. **Build the executable**
   ```bash
   g++ -o compiler lex.cpp parser.tab.c -lfl
   ```

## 💡 Features

- ✅ Complete lexical analysis with token recognition
- ✅ Context-free grammar implementation
- ✅ Symbol table management
- ✅ Error detection and reporting
- ✅ Multiple parser variations for experimentation
- ✅ Modular design for easy extension

## 🎯 Usage

Run the compiler on a C source file:

```bash
./compiler input.c
```

The compiler will process the input file through all compilation phases and generate the corresponding output.

## 📚 Learning Outcomes

This project helped me understand:

- How compilers translate high-level code to machine code
- The role of formal grammars in programming languages
- Lexical and syntactic analysis techniques
- Symbol table design and management
- Error handling in compilers

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements or bug fixes!

## 📄 License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

## 👤 Author

**Abhishek**
- GitHub: [@darkphoenix2208](https://github.com/darkphoenix2208)
- Project: [C Compiler Design from Scratch](https://github.com/darkphoenix2208/C_Compiler_DESIGNING_FROM_SCRATCH)

---

⭐ If you find this project helpful, please give it a star!

*Built with 💻 and ☕ and darkphoenix2208 | © 2026*
