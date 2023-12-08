# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

## Bulletin

* [PunC 1.0 Announcement](https://medium.com/@andrew_johnson_4/project-milestone-punc-1-0-and-lm-specifications-61602ca551fb)

## My TODO List

1. [Relog Standard Library](https://github.com/andrew-johnson-4/InPlace/issues/7) having good performance and good feature completeness
   * Making Relog powerful is useful because it allows side-effects to be well-typed (nominally)
   * Optimize Relog reduction strategy (closed forms can already be fast, but it would be nice if standard reduction was quick too)
      * The main bottleneck right now for this is to build an efficient data structure for contexts
      * cloning into inner scopes are currently a deep copy
      * similarly destructive bindings are also a deep copy 
3. Port a Basic Codegen for LM: [chibi.lm](https://github.com/rui314/chibicc)
4. Rewrite LSTS in LM with PunC/Relog verification
5. Optimize LSTS codegen for some common (CPU,GPU,Circuit Synthesis) use cases
6. Extend LSTS to support the full founding [Prelude](https://github.com/andrew-johnson-4/perplexity/blob/main/categorical_prelude.md)

## Request a Service

I build things for the web or your local computer. Have an idea? Feel free to reach out:
* andrew[at]subarctic.org

or just feel free to say hi! 👋
