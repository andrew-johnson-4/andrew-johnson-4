## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> $$ y^2 = x^3 + ax + b $$
>
> <div align="center">When a program has nothing surprising to say, it should say nothing. — Rule of Silence</div>

### [LSTS Examples & Documentation](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/)

### 2025 Roadmap (Working towards a verified kernel language)

<div>
  <p>
    <img align="left" height="100" src="https://github.com/andrew-johnson-4/andrew-johnson-4/blob/main/07723b62-1f56-4e7f-97d0-98423669a1da.png?raw=true"/>
    <span>If you are considering trying to learn LSTS, please wait until the V3 compiler and v1.0 language standard comes on line.
    Hopefully this will happen late 2025-early 2026.</span>
  </p>
  <br/>
  <br/>
  <br/>
</div>



* ✓ [1.22.0 Type-Directed Macros](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.22.0)
* ✓ [1.23.0 Compiler 100% Written in LSTS](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.23.0)
* ✓ [1.24.0 Garbage Collection](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.24.0)

### Work-Order Priorities

* FAST Memory-Efficient Compiler (hopefully by the end of 2025-ish)
* C Frontend to be mostly standards compliant + some common C extensions
* LSTS to feel like a stable language
   * LSTS has lots of cool features (mission accomplished)
   * now it just needs to soundly and efficiently compile stuff
   * typechecking (full soundness proofs) with some notable exceptions that are theoretically unavoidable
      * template divergence (sometimes we can catch this, but in general it is undecidable)
      * principle of nominal trust
   * good error messages for all kinds of unsound programs
   * FAST code and compilation speeds (sub 1s self-compilation on Github task runners)
   * standard library makeover
      * linear typesafe pointer management
      * no memory leaks / implicit reference-counted GC
      * some generics to avoid over-specialization
      * benchmarks vs C++, Rust, ML

### Upcoming Planned Features
* Language Standard v1.0
* Linear Garbage Collection
   * this is a library, not a core feature (it just depends on linear/phi-types with del hooks)
* Representation Selection for Closures with auto GC
   * oddly enough, this is also a library, not a hardcoded compiler feature

### Product Oriented Goals
* Turn LM into a decent ["yak herder"](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/wiki/Unopinionated-Philosophy#yak-herding-not-yak-shaving) for C programming
   * the goal here is for people to interact meaningfully with C codebases without actually having to touch C
