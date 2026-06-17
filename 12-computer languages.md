# Computer Languages

## Introduction

Computers understand only machine language (binary code). Humans, however, use natural languages such as English.

To communicate with computers, different types of computer languages have been developed. These languages allow programmers to write instructions that computers can understand and execute.

---

# What is a Computer Language?

## Definition

A Computer Language is a language used to write instructions and programs that can be executed by a computer.

## Purpose

* Communicate with computers
* Develop software applications
* Solve problems using programs
* Control hardware devices

---

# Types of Computer Languages

```text
Computer Languages
│
├── Machine Language
├── Assembly Language
└── High-Level Language
```

---

# 1. Machine Language

## Definition

Machine Language is the lowest-level programming language understood directly by the computer.

It consists of binary digits (0 and 1).

## Example

```text
10110010
11001001
01010101
```

## Characteristics

* Uses only 0 and 1
* Directly understood by CPU
* Fast execution
* Difficult for humans to read and write

## Advantages

* Fast execution
* No translator required

## Disadvantages

* Difficult to understand
* Error-prone
* Machine dependent

---

# 2. Assembly Language

## Definition

Assembly Language uses symbolic codes called mnemonics instead of binary numbers.

## Example

```text
MOV A, B
ADD A, C
SUB A, D
```

## Characteristics

* Easier than machine language
* Uses symbols and abbreviations
* Requires an assembler
* Machine dependent

## Advantages

* Easier to understand than binary
* Faster execution

## Disadvantages

* Difficult compared to high-level languages
* Machine dependent

---

# 3. High-Level Language

## Definition

A High-Level Language is a programming language that uses English-like statements and is easier for humans to understand.

## Examples

* C
* C++
* Java
* Python
* R
* JavaScript

## Example

```python
print("Hello World")
```

## Characteristics

* Easy to learn
* Easy to write and debug
* Portable across systems
* Requires a translator

## Advantages

* User-friendly
* Faster development
* Easier maintenance

## Disadvantages

* Slower than machine language
* Requires translation

---

# Language Translators

Computers understand only machine language.

Programs written in Assembly Language and High-Level Languages must be translated into machine language.

Types of translators:

```text
Language Translators
│
├── Compiler
├── Interpreter
└── Assembler
```

---

# 4. Compiler

## Definition

A Compiler translates an entire program into machine language at once before execution.

## Working

```text
Source Program
      ↓
   Compiler
      ↓
Machine Code
      ↓
Execution
```

## Examples

* C Compiler
* C++ Compiler

## Advantages

* Faster execution
* Detects errors after compilation

## Disadvantages

* Compilation takes time

---

# 5. Interpreter

## Definition

An Interpreter translates and executes one line of code at a time.

## Working

```text
Source Program
      ↓
 Interpreter
      ↓
 Execute Line by Line
```

## Examples

* Python Interpreter
* JavaScript Engine

## Advantages

* Easy debugging
* Immediate execution

## Disadvantages

* Slower execution

---

# Difference Between Compiler and Interpreter

| Compiler                       | Interpreter              |
| ------------------------------ | ------------------------ |
| Translates entire program      | Translates line by line  |
| Faster execution               | Slower execution         |
| Errors shown after compilation | Errors shown immediately |
| Example: C                     | Example: Python          |

---

# 6. Assembler

## Definition

An Assembler converts Assembly Language into Machine Language.

## Working

```text
Assembly Language
        ↓
     Assembler
        ↓
   Machine Language
```

## Example

```text
ADD A, B
```

Converted into binary instructions understood by the CPU.

---

# Language Evolution

```text
Machine Language
        ↓
Assembly Language
        ↓
High-Level Language
```

As languages evolved, programming became easier and more efficient.

---

# Comparison of Computer Languages

| Feature           | Machine Language | Assembly Language | High-Level Language  |
| ----------------- | ---------------- | ----------------- | -------------------- |
| Readability       | Very Difficult   | Moderate          | Easy                 |
| Speed             | Very Fast        | Fast              | Moderate             |
| Portability       | No               | No                | Yes                  |
| User-Friendly     | No               | Limited           | Yes                  |
| Translator Needed | No               | Assembler         | Compiler/Interpreter |

---

# Importance of Computer Languages

Computer languages help:

* Develop software
* Create websites
* Build mobile apps
* Analyze data
* Perform scientific computing
* Support Bioinformatics research

---

# Summary

* Computer languages are used to communicate with computers.
* Machine Language uses binary digits.
* Assembly Language uses mnemonics.
* High-Level Languages are easy to understand.
* Compiler translates an entire program.
* Interpreter translates line by line.
* Assembler converts Assembly Language to Machine Language.

---

# Interview Questions

### Q1. What is a Computer Language?

A language used to write instructions for a computer.

### Q2. Which language is directly understood by the computer?

Machine Language.

### Q3. What are the main types of computer languages?

* Machine Language
* Assembly Language
* High-Level Language

### Q4. What is Assembly Language?

A language that uses mnemonics instead of binary code.

### Q5. Give examples of High-Level Languages.

* C
* C++
* Java
* Python

### Q6. What is a Compiler?

A translator that converts the entire program into machine language at once.

### Q7. What is an Interpreter?

A translator that converts and executes code line by line.

### Q8. What is an Assembler?

A translator that converts Assembly Language into Machine Language.

### Q9. Which is easier to learn: Machine Language or High-Level Language?

High-Level Language.

### Q10. Which translator is used for Assembly Language?

Assembler.

---

# Quick Revision

```text
Machine Language
↓
Binary (0,1)

Assembly Language
↓
Mnemonics (ADD, MOV)

High-Level Language
↓
C, C++, Java, Python

Compiler → Whole Program
Interpreter → Line by Line
Assembler → Assembly to Machine
```

## Memory Trick

```text
Machine → Binary
Assembly → Mnemonics
High-Level → English-like

Compiler → Complete Program
Interpreter → Individual Lines
Assembler → Assembly Language
```
