# Quazi Programming Language

Quazi is an independent, low-level systems programming language engineered for performance, strictness, and deterministic execution. 

The organization develops and maintains the core language infrastructure, including the reference compiler (`quazistrap`), the custom bytecode ecosystem (QZI), and the standard library (`std`).

## Language Components

* **[`bootstrap`](https://github.com/quazilang/quazistrap):** Reference bootstrap compiler written in Rust, featuring semantic analysis, QZI bytecode execution, and x86_64 code generation.
* **`quazi`:** Self-hosting compiler implementation and primary language repository.
* **[`std`](https://github.com/quazilang/std):** Standard library providing memory management, system calls, runtime intrinsics, and I/O abstractions.
* **[`tree-sitter`](https://github.com/quazilang/tree-sitter):** Tree-sitter grammar specification for syntax highlighting, LSP integration, and editor tooling.
* **[`docs`](https://github.com/quazilang/docs):** Official language specification, architecture documentation, and usage guides.

## Resources

* **Website:** [quazilang.github.io](https://quazilang.github.io)
* **Codeberg Mirror:** [codeberg.org/quazilang](https://codeberg.org/quazilang)
