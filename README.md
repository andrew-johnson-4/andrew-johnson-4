## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> $$ y^2 = x^3 + ax + b $$

### [LSTS Examples & Documentation](https://andrew-johnson-4.github.io/lsts-language-reference/)

### 2025 Roadmap (Working towards a verified kernel language)

* ✓ [1.0.0 Bootstrap Compiler](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.0.0) 🥳🎉🎁
* ✓ [1.21.0 Core Type System Revamp](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.21.0)
* ✓ [1.22.0 Type-Directed Macros](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/releases/tag/1.22.0)

### Work-Order Priorities

* C Frontend to be mostly standards compliant + some common C extensions
* LSTS frontend to feel like a fully formed language

### Upcoming Planned Features
* Language Standard v1.0
* Linear Garbage Collection
   * this is a library, not a core feature (it just depends on linear/phi-types with del hooks)
* Representation Selection for Closures with auto GC

### Product Oriented Goals
* Turn LM into a decent ["yak herder"](https://github.com/Lambda-Mountain-Compiler-Backend/lambda-mountain/wiki/Unopinionated-Philosophy#yak-herding-not-yak-shaving) for C programming
   * the goal here is for people to interact meaningfully with C codebases without actually having to touch C
