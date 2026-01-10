## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> $$ y^2 = x^3 + ax + b $$
>
> <div align="center">When a program has nothing surprising to say, it should say nothing. — Rule of Silence</div>
> <br>
> <div align="center">Mountains cannot be surmounted except by winding paths. — Johann Wolfgang von Goethe</div>


### [LSTS Examples & Documentation](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/)

### 2025 Roadmap (Working towards a verified kernel language)

<div>
  <p>
    <img align="left" height="100" src="https://github.com/andrew-johnson-4/andrew-johnson-4/blob/main/07723b62-1f56-4e7f-97d0-98423669a1da.png?raw=true"/>
    <span>If you are considering trying to learn LSTS, please wait until the V3 compiler and v1.0 language standard comes on line.
    v1.0 is the big goal for 2026.</span>
  </p>
  <br/>
  <br/>
  <br/>
</div>



* ✓ [1.22.0 Type-Directed Macros](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.22.0)
* ✓ [1.23.0 Compiler 100% Written in LSTS](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.23.0)
* ✓ [1.24.0 Garbage Collection](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.24.0)

### Work-Order Priorities

* FAST Memory-Efficient Compiler (50% done, hopefully by start of spring 2026)
* C Frontend to be mostly standards compliant + some common C extensions (project for summer 2026)
* LSTS to feel like a stable language
   * LSTS has lots of cool features (mission accomplished)
   * now it just needs to soundly and efficiently compile stuff
   * typechecking (full soundness proofs) with some notable exceptions that are theoretically unavoidable
      * template divergence
         * sometimes we can catch this, but in general it is undecidable
      * principle of nominal trust
         * axioms can be frozen, but they can't be removed
         * all good theorem provers have this problem if they allow new axioms to be declared
   * good error messages for all kinds of unsound programs
   * FAST code and compilation speeds (sub 1s self-compilation on Github task runners)
   * [✓] standard library makeover
      * [✓] linear typesafe pointer management
      * [✓] no memory leaks / implicit reference-counted GC
      * some generics to avoid over-specialization
      * benchmarks vs C++, Rust, ML
* [cold-start script](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/issues/1821) for collaborative editing LSTS with AI
  
### Upcoming Planned Features
* Language Standard v1.0
* Full C Support
* Cold-start script so that anyone unfamiliar with LSTS can use an effectively pretrained AI to start collaboratively "vibe coding" in LSTS
   * LSTS (and theorem-proving specialized languages in general) are particularly well-suited to work with AI
   * the AI can "fail and learn" faster
   * the programmer can "oops" more
   * etc.
   * the development trajectories could then hopefully be more high-level, objective-oriented, product-oriented
* Representation Selection for Closures with auto GC
   * oddly enough, this is also a library, not a hardcoded compiler feature
* Fix C backend to be a true assembler
   * currently there is some hard-coded logic that is technically a "compiler" backend
   * we need to just expose all of these features directly to return to being a true assembler
   * these are some pretty fun features like uniqueness types etc.
      
### Product Oriented Goals
* [probably.lm](https://github.com/andrew-johnson-4/probably.lm) Rational programming library
   * Simply put this allows neural nets and traditional code objects to integrate naturally
   * You don't need to understand math above boolean logic to program
   * Active learning if we can get performance good enough
