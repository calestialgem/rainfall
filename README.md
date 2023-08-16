# Rainfall

Rainfall is the original compiler for the Thrice programming language.
Transpiles Thrice to C.

## Roadmap

1. Write Rainfall in Thrice.
2. Write another version in an already implemented language.
3. Use the second version to compile the first one.

Above steps are going to be used for implementing Thrice in Thrice. Writing the
compiler first would solidify the language's design and be a test for any other
implementation.

## Goals

For the initial version, only a small set of highly necessary features must be
asked from the compiler. This subset of Thrice must include the fallowing:

- Reading and writing files and directory entries.
- Executing commands and processes.
- References.
- Procedures.
- Product and sum types.
- Memory allocation.
- Logging and exiting.
- Most expressions and statements.
- Number, character and string constants.
- Variables.
- Pattern matching.

Some of these capabilities can be easily captured with:

- Calling functions in the C standard library.
- Equivalents for built-in C types.
- Pointers.

## License

Licensed under GPL 3.0 or later.

---

Copyright (C) 2023 Cem Geçgel <gecgelcem@outlook.com>
