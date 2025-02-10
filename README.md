## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> $$ y^2 = x^3 + ax + b $$

### [LSTS Examples & Documentation](https://andrew-johnson-4.github.io/lsts-language-reference/)

### 2024 Roadmap (Working towards a verified kernel language)

* ✓ [1.0.0 Bootstrap Compiler](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.0.0) 🥳🎉🎁
* ✓ [1.19.0 Basic support for LSTS syntax](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.19.1)
* ✓ [1.20.0 Phi Types](https://github.com/andrew-johnson-4/lambda-mountain/releases/tag/1.20.0)

### Work-Order Priorities

Having completed about 50% of housekeeping, it is now time to return to feature development.
This arc is focused on bringing the C frontend up to accepting all standards compliant ANSI C.
This hopefully won't take a terribly long time.

**TODO:**
* 40 grammar rules to go to get parser working
* C AST -> LM AST converter

### Upcoming Planned Features
* rewrite compiler internals in LSTS (focus on how things should be, rather than how things are)
  * some of the internal APIs can be stabilized
* Language Standard v1.0
* Linear Garbage Collection
   * this is a library, not a core feature (it just depends on linear/phi-types with del hooks)
* Representation Selection for Closures with auto GC

