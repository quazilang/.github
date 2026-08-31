# Quazi Programming Language

### This organization develops and maintains the entire Quazi programming language infrastructure.

**Quazilang** is a standalone, multi-level, high-performance, and memory-safe systems programming language that achieves full memory safety without a garbage collector through a compile-time borrow checker and Whole-Program Optimization (WPO). Built around Whole-Program Analysis, Compilation, and Optimization, its intelligent analyzer traverses the call graph directly from the entry point, emitting bytecode exclusively for the precise code paths executed. Modules, standard library imports, and source files function header-style at compile time, eliminating bloat and unneeded dependencies. The entire compilation process produces a single unified object file generated entirely in memory - which can be executed instantly via the LazyJIT compiler or compiled directly into a single, highly optimized native binary without intermediate runtime or LLVM overhead.

## Hello world

```quazi
import std.io;

fn main() i32 {
    io.println("Hello, world!");
    ret 0;
}
```

## Language Components

* **[`quazistrap`](https://github.com/quazilang/quazistrap):** Reference bootstrap compiler written in Rust.
* **`quazi`:** Self-hosting compiler implementation and primary language repository.
* **[`std`](https://github.com/quazilang/std):** Standard library providing memory management, system calls, runtime intrinsics, and I/O abstractions.
* **`quazi-analyzer`:** Language Server Protocol (LSP) implementation providing code intelligence, diagnostics, and editor support.
* **[`website`](https://github.com/quazilang/website):** Source code for the [Quazilang website](https://quazilang.github.io).
* **[`docs`](https://github.com/quazilang/docs):** Official language specification, architecture documentation, and usage guides.
* **[`tree-sitter`](https://github.com/quazilang/tree-sitter):** Tree-sitter grammar specification for syntax highlighting, LSP integration, and editor tooling.

## Resources

* **Website:** [quazilang.github.io](https://quazilang.github.io)
* **Codeberg:** [codeberg.org/quazilang](https://codeberg.org/quazilang)
