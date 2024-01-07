# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> One of the most popular apps on phones are timers. The user already knows that they need to remember something, but they might need to be reminded. Assisted Reasoning is sort of like that: a tea timer for logic.

##  On Open-Source

> Imagine if Example Co. claimed ownership over the English language and tried to make international air traffic controllers pay for the rights to use it. People would get upset, right?

There are enough programmers in the world now that Body Politics is starting to take hold.
Legal Disputes can no longer be resolved between "two nerds disagreeing", but rather must be addressed to a larger non-uniform group of shareholders.
If you want to interact with active language communities, you should be prepared for this variety of disputes and conflict resolution tactics.

## [On Trusting Trust](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)

I don't want to distrust everyone, but I also don't want to trust everyone.

## My Projects

### 10000 foot view

* [PunC](https://github.com/andrew-johnson-4/PunCalculus) is an Intermediate Representation
* [Relog](https://github.com/andrew-johnson-4/InPlace) is a Type System
* [λ☶](https://github.com/andrew-johnson-4/-) is a Compiler Backend
  * Combines PunC, Relog, and a simple S-Expression parser to create a typed fragment assembler
* [LSTS](https://github.com/andrew-johnson-4/LSTS) is a Compiler Frontend

### 2024 Roadmap

* Bootstrap Compiler 🥳🎉🎁

The bootstrap compiler implements eval-soft.
The compiler will be considered complete when it can be shown that no valid program sent to eval-soft will crash or return a non-normal result.
The one exception to this rule is Stack Overflow, which is a defined behavior with a non-normal result.

### My TODO List

* ✓ Bootstrap Compile a CLI that dumps S-Expression fragments
* Bootstrap Compile a CLI that normalizes then dumps S-Expression fragments
   * ✓ Atom convenience functions
   * ✓ Cons convenience functions
   * user-defined functions
     * unsugared functions: `λ. tail $_`
       * `$_` yields this in expression context (is often a noop)
       * apply user-defined functions as bound variables
     * sugared functions: `λx y z. XYZ x y z`
     * open problem for typechecking: `let` is a macro that manipulates the stack frame, how should this be modelled?
       * assumptions about the registers and memory model are implicit parameters to all functions
       * a simpler example might be to model the type signature of `push %ax`
   * eval-soft
* Bootstrap Compile a CLI that parses, normalizes, then dumps S-Expression fragments
* Bootstrap Compile a CLI that parses, verifies, normalizes, then dumps S-Expression fragments
* Bootstrap Compile a fast CLI that parses, verifies, normalizes, then dumps S-Expression fragments
* Freeze a "canonical" bootstrap version

### Request a Service

I build things for the web or your local computer. Have an idea? Feel free to reach out:
* andrew[at]subarctic.org

or just feel free to say hi! 👋
