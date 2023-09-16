# Hi, I'm Andrew Johnson ![](https://komarev.com/ghpvc/?username=andrew-johnson-4)

“My life depended on 150,000 pieces of equipment – each bought from the lowest bidder.”

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
* The Greedy Rule (maximalist program utility)
* The Colorblind Rule (maximalist proof utility)

However, interestingly, these two rules can't be meaningfully unified;
the result of both rules used simultaneously leads immediately to zero information gain (bottom).
