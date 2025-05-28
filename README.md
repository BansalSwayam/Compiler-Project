# Compiler-Project

# AQL Compiler

## 📘 Project Overview

The **AQL Compiler** is a lightweight compiler designed for the **Abstract Query Language (AQL)**, showcasing key concepts in **lexical analysis**, **syntax parsing**, and **compiler construction** using `Flex` and `Bison`. It is an educational compiler intended to parse, validate, and interpret simplified AQL programs.

This project was built as part of an academic exploration of compiler design and demonstrates practical implementation of **lexer-parser workflows**, **grammar rule specification**, and **compilation techniques** in C.

---

## 🧠 Key Concepts Implemented

- ✅ **Lexical Analysis** (via `aql.l` using Flex)
- ✅ **Syntax Parsing** (via `aql.y` using Bison/Yacc)
- ✅ **Token and Grammar Definitions**
- ✅ **Error Reporting for Syntax Errors**
- ✅ **Input Redirection for AQL Source Files**
- ✅ **Automated Build System (Makefile)**

---

## 🗂️ Project Structure

AQL-Compiler/
├── aql.l # Lexer rules (Flex)
├── aql.y # Grammar rules (Bison/Yacc)
├── Makefile # Build instructions
├── test1.aql # Sample AQL input program
├── y.tab.c # Generated parser C file
├── y.tab.h # Generated parser header
├── lex.yy.c # Generated lexer C file
├── aql_parser # Output compiler executable (after building)


