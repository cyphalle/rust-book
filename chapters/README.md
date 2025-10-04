# The Rust Programming Language - Chapter Extracts

This directory contains text extracts from "The Rust Programming Language" (2018 Edition) by Steve Klabnik and Carol Nichols, split into individual chapter files for easier reading and reference by AI agents.

## Chapter Files

### Core Chapters

| File | Chapter | Title | Topics |
|------|---------|-------|--------|
| `chapter_01_getting_started.txt` | 1 | Getting Started | Installation, Hello World, Cargo basics |
| `chapter_02_guessing_game.txt` | 2 | Programming a Guessing Game | First hands-on project, basic syntax |
| `chapter_03_common_concepts.txt` | 3 | Common Programming Concepts | Variables, data types, functions, control flow |
| `chapter_04_ownership.txt` | 4 | Understanding Ownership | Ownership, borrowing, references, slices |
| `chapter_05_structs.txt` | 5 | Using Structs to Structure Related Data | Defining structs, methods, associated functions |
| `chapter_06_enums.txt` | 6 | Enums and Pattern Matching | Enums, Option, match, if let |
| `chapter_07_packages_crates_modules.txt` | 7 | Managing Growing Projects | Packages, crates, modules, paths, use keyword |
| `chapter_08_collections.txt` | 8 | Common Collections | Vectors, strings, hash maps |
| `chapter_09_error_handling.txt` | 9 | Error Handling | panic!, Result, ? operator |
| `chapter_10_generics_traits_lifetimes.txt` | 10 | Generic Types, Traits, and Lifetimes | Generic data types, traits, lifetime annotations |
| `chapter_11_automated_tests.txt` | 11 | Writing Automated Tests | Writing tests, running tests, test organization |
| `chapter_12_io_project.txt` | 12 | An I/O Project | Building a command line program (grep clone) |
| `chapter_13_iterators_closures.txt` | 13 | Functional Language Features | Closures, iterators, performance |
| `chapter_14_cargo_crates_io.txt` | 14 | More About Cargo and Crates.io | Release profiles, publishing crates, workspaces |
| `chapter_15_smart_pointers.txt` | 15 | Smart Pointers | Box, Rc, RefCell, reference cycles |
| `chapter_16_concurrency.txt` | 16 | Fearless Concurrency | Threads, message passing, shared state |
| `chapter_17_oop_features.txt` | 17 | Object-Oriented Programming Features | Trait objects, OOP patterns in Rust |
| `chapter_18_patterns_matching.txt` | 18 | Patterns and Matching | Pattern syntax, refutability, match guards |
| `chapter_19_advanced_features.txt` | 19 | Advanced Features | Unsafe Rust, advanced traits, types, functions, macros |
| `chapter_20_multithreaded_server.txt` | 20 | Final Project | Building a multithreaded web server |

### Reference Material

| File | Content |
|------|---------|
| `chapter_appendices.txt` | Appendices A-E: Keywords, Operators, Derivable Traits, Development Tools, Editions |

## File Format

All files are plain text (`.txt`) extracted from the PDF using `pdftotext`. They maintain the original formatting as much as possible, though some layout elements may not perfectly translate from PDF to text format.

## Usage Notes

- Each chapter file is self-contained and can be read independently
- Code examples are included inline within the text
- Page numbers from the original book are preserved in the text
- For the original formatted PDF, see `../The rust programming language.pdf`

## Suggested Reading Order

The book is designed to be read sequentially, as later chapters build on concepts from earlier ones. However, you can skip Chapter 2 (the guessing game project) and return to it later if you prefer to learn concepts before building a complete project.

Key chapters for core Rust understanding:
- **Chapter 4** (Ownership) - Essential for understanding Rust's memory model
- **Chapter 6** (Enums & Pattern Matching) - Critical for idiomatic Rust
- **Chapter 10** (Generics, Traits, Lifetimes) - Core type system concepts
- **Chapter 15** (Smart Pointers) - Understanding Rust's reference types

## Source

Extracted from: `The rust programming language.pdf`  
Book Version: 2018 Edition  
Authors: Steve Klabnik and Carol Nichols  
Publisher: No Starch Press
