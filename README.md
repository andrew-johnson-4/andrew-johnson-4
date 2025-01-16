## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> Carving is easy, you just go down to the skin and stop.
>
> -- Michelangelo

### [LSTS Examples & Documentation](https://andrew-johnson-4.github.io/lsts-language-reference/)

### 2024 Roadmap (Working towards a verified kernel language)

* ✓ [1.0.0 Bootstrap Compiler](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.0.0) 🥳🎉🎁
* ✓ [1.19.0 Basic support for LSTS syntax](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.19.1)
* ✓ [1.20.0 Phi Types](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.20.0)

### Work-Order Priorities

Now having completed new feature capacity to handle complex data structures like Umbra Strings,
the compiler is long overdue for some housekeeping.
The feature set will therefore be frozen for a while to spend some time on compiler internals.
* breaking compiler into independent compilation units with unit tests
* improving performance with high-level and low-level optimizations

### Upcoming Planned Features
* rewrite compiler internals in LSTS (focus on how things should be, rather than how things are)
  * some of the internal APIs can be stabilized, just written with a different syntax
* Language Standard v1.0
* Linear Garbage Collection
   * this is a library, not a core feature (it just depends on linear/phi-types with del hooks)
* Representation Selection for Closures with auto GC
* Correctness Proofs with Coq (100% verifiable semantics)

