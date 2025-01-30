## Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> Statistically interpreting natural language is like following signs to get to a destination.
> There are lots of signs pointing in different directions and many places that you might want to go.
>
> Improving natural language processing then takes two forms: better navigation and better signage.

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
  * some of the internal APIs can be stabilized
* Language Standard v1.0
* Linear Garbage Collection
   * this is a library, not a core feature (it just depends on linear/phi-types with del hooks)
* Representation Selection for Closures with auto GC

