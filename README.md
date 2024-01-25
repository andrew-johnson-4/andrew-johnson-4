# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> One of the most popular apps on phones are timers. The user already knows that they need to remember something, but they might need to be reminded. Assisted Reasoning is sort of like that: a tea timer for logic.

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
* ✓ Bootstrap Compile a CLI that normalizes then dumps S-Expression fragments
* ✓ Bootstrap Compile a CLI that parses, normalizes, then dumps S-Expression fragments
* Bootstrap Compile a CLI that parses, normalizes, then assembles input files including itself (actually bootstrapping at this point)
  * ✓ "Create File" system call
  * ✓ Use `g.lm` to compile an empty program
  * ✓ Global Variables
  * ✓ uuid convenience function
  * ✓ Use `g.lm` to compile hello world
  * Use `g.lm` to compile and run the whole test suite [(34 / 77 passing)](https://github.com/andrew-johnson-4/-/issues/42)
  * Use `g.lm` to compile itself, a full featured compiler
  * Distribute bootstrapped compiler with `cargo install` instead of hosted compiler
* Freeze a "canonical" bootstrap version

### Request a Service

I build things for the web or your local computer. Have an idea? Feel free to reach out:
* andrew[at]subarctic.org

or just feel free to say hi! 👋
