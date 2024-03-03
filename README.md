# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> One of the most popular apps on phones are timers. The user already knows that they need to remember something, but they might need to be reminded. Assisted Reasoning is sort of like that: a tea timer for logic.

### 2024 Roadmap (Working towards a verified kernel language)

* ✓ [1.0.0 Bootstrap Compiler](https://github.com/andrew-johnson-4/-/releases/tag/1.0.0) 🥳🎉🎁
* ✓ [1.6.0 Production Compiler](https://github.com/andrew-johnson-4/-/releases/tag/1.6.0)
* ✓ [1.10.0 Ad-Hoc Specialization and Macros](https://github.com/andrew-johnson-4/-/releases/tag/1.10.0)
* 100% compiled code when --strict mode is enabled
  * direct .text .data fragments
  * default instruction set ( x86-64 )
  * Primitive Data Types (Int, Float, ...)
  * Operations on Primitive Types (+, -, /, ...)
  * Basic Data Structures: Structs, Tagged Unions
  * Specialized Explicit Context: Typesafe Register Allocation, Stack State, Heap State
  * Arbitrary Custom Data Structures (raw data fragment based definitions)
  * Arbitrary Custom Code Structures (raw code fragment based definitions)
  * Remove all S-Expression default types from compiler (enforce with --strict)
  * Named Accessors for Struct Types (.offset:Expr->Int), (set.offset:(Expr,Int)->Nil) (different functions have different calling conventions)
  * benchmark vs some other compilers (OCaml, Rust, C) 📈📈📈
* Garbage Collection
  * [Atom Allocator](https://github.com/andrew-johnson-4/lm_skip_list_atom_allocator) (defined as a custom data structure)
  * [Cons Allocator](https://github.com/andrew-johnson-4/lm_generational_cons_allocator) (defined as a custom data structure)

### Benchmarks are silly but we still do them (yes Dynamic Code is slow)

![Fibonacci](https://raw.githubusercontent.com/andrew-johnson-4/andrew-johnson-4/master/fibonacci.svg)
