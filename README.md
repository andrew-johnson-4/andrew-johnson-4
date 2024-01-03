# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> One of the most popular apps on phones are timers. The user already knows that they need to remember something, but they might need to be reminded. Assisted Reasoning is sort of like that: a tea timer for logic.

## Bulletin

* [PunC 1.0 Announcement](https://medium.com/@andrew_johnson_4/project-milestone-punc-1-0-and-lm-specifications-61602ca551fb)

## 10000 foot view

* [PunC](https://github.com/andrew-johnson-4/PunCalculus) is an Intermediate Representation
* [Relog](https://github.com/andrew-johnson-4/InPlace) is a Type System
* [λ☶](https://github.com/andrew-johnson-4/-) is a Compiler Backend
  * Combines PunC, Relog, and a simple S-Expression parser to create a typed fragment assembler
* [LSTS](https://github.com/andrew-johnson-4/LSTS) is a Compiler Frontend

## My TODO List

1. [Bootstrap LM](https://github.com/andrew-johnson-4/-/issues/14)
   * ✓ Bootstrap Compile a CLI that dumps S-Expression fragments
   * Bootstrap Compile a CLI that normalizes then dumps S-Expression fragments
   * Bootstrap Compile a CLI that parses, normalizes, then dumps S-Expression fragments
   * Bootstrap Compile a CLI that parses, verifies, normalizes, then dumps S-Expression fragments
   * Bootstrap Compile a fast CLI that parses, verifies, normalizes, then dumps S-Expression fragments
   * Freeze a "canonical" bootstrap version
3. [Relog Standard Library](https://github.com/andrew-johnson-4/InPlace/issues/7) having good performance and good feature completeness
   * Making Relog powerful is useful because it allows side-effects to be well-typed (nominally)
4. Optimize LSTS codegen for some common (CPU,GPU,Circuit Synthesis) use cases
5. Extend LSTS to support the full founding [Prelude](https://github.com/andrew-johnson-4/perplexity/blob/main/categorical_prelude.md)

## Request a Service

I build things for the web or your local computer. Have an idea? Feel free to reach out:
* andrew[at]subarctic.org

or just feel free to say hi! 👋
