# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

> One of the most popular apps on phones are timers. The user already knows that they need to remember something, but they might need to be reminded. Assisted Reasoning is sort of like that: a tea timer for logic.

### 2024 Roadmap

* ✓ [1.0.0 Bootstrap Compiler](https://github.com/andrew-johnson-4/-/releases/tag/1.0.0) 🥳🎉🎁
* ✓ [1.1.0 Typesafe Compiler](https://github.com/andrew-johnson-4/-/releases/tag/1.1.0)
* More Practicality for Real Usage (1.2.0)
  * dynamic heap allocation
    * linked list of isoheap pages is a good default
    * STDLIB/default-atom-allocator.lm
      * center on (allocate-append-atom base-cstring new-cstring) method
      * `Page<PageSize=Int> { last-string-head: char*, last-string-tail: char*, next-page: Page<PageSize>, page-data: char[PageSize] }`
      * not to be used for dynamically extending strings (clone-rope is still recommended for best performance)
    * STDLIB/default-cons-allocator.lm
      * center on (allocate-cons()) method
    * page table heads are static globals (how can this be declared in the stdlib modules?)
      * They aren't S-Expressions, so some basic notion of data-type is necessary?
      * no pages are allocated to begin so overhead is one word for each allocator
  * atom deduplication (this is a simple optimization)
  * relative imports during build
  * doby based build manager

### Request a Service

I build things for the web or your local computer. Have an idea? Feel free to reach out:
* andrew[at]subarctic.org

or just feel free to say hi! 👋
