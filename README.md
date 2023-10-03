# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

“I am afraid sometimes that what I say is not what others hear, and that what I mean is not what others understand.”

$$greedy \ infer \quad \frac{f:A \to B \quad f:B \to C}{f:A \to C}$$

$$cannot \ determine \ color \quad \frac{f:A \to B \quad f:B \to C \quad f:A \to C}{\bot}$$


 Combination         | Result                                  |
---------------------|-----------------------------------------|
 Neither             | Inference is dumb                       |
 Greedy              | Inference is maybe too smart            |
 ColorBlind          | Inference is maybe too conservative     |
 Greedy + ColorBlind | Inference fails a lot                   |

You can use formal language to ask questions (proofs) or to write commands (programs).
Heading further in either of these directions leads to
* The Greedy Rule (maximalist inference/program utility)
* The Colorblind Rule (maximalist confidence/proof utility)

However, interestingly, these two rules can't be meaningfully unified;
the result of both rules used simultaneously leads immediately to zero information gain (bottom).

## derivation of Cannot Determine Color

For a term to be ambiguous, at least the domain or range must be ambiguous. If both the domain and range are known, then there is no ambiguity. The problem arises when a triangle is formed by the ambiguous binding. It then becomes impossible to reduce the ambiguity to a single candidate; you always end up with at least two candidates.

## why ambiguity may be useful

"ambiguity" is relevant to typing because when combined with plural types it creates a direct equivalence to disjunctive normal form from Boolean logic.
