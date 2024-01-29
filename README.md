# Brainfuck Interpreter

This is a simple Brainfuck interpreter written in OCaml. It can read Brainfuck programs from a file and execute them on a tape.

## Table of Contents
- [Usage](#usage)
- [File Format](#file-format)
- [Example](#example)
- [Notes](#notes)

## Usage

To use the Brainfuck interpreter, you can run the provided OCaml executable as follows:

```bash
$ ocamlopt -o brainf brainfuck_interpreter.ml
$ ./brainf <filename>

```

## File Format

The Brainfuck program should be written in a separate file. The interpreter expects a valid Brainfuck code in this file.

Replace `<filename>` in the usage example with the actual filename of your Brainfuck program.

## Notes

- The interpreter supports Brainfuck programs with a tape size of 160,000 cells.
- The `testing` function in the code contains a sample Brainfuck program. You can modify this function to test your interpreter with different programs.
- Ensure that your Brainfuck programs adhere to the syntax rules of the Brainfuck language.

## File Format

The Brainfuck program should be written in a separate file. The interpreter expects a valid Brainfuck code in this file.
