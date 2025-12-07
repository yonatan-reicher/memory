# Research

Hopefully, this will be the last file I open for remembering what Shachar and I
discussed.

Here I write things a work log of what I did and summaries of meetings.

Currently I am looking into LeanEgg and comparing it with grind. Some time ago,
I wrote that I had issues compiling LeanEgg on Windows, and on Wsl. Apparently,
it also has a docker image in the git repo, so I should try that.

## Meeting Summaries

### 2025-12-02
I should leave the monads behind for now and focus on making Lean better for
maths and proofs. For next week:
- [ ] read the test cases section in
      [this paper](https://steuwer.info/files/publications/2026/POPL-Lean-Egg.pdf)
- [ ] read the evaluation section in
      [this paper](https://cfaed.tu-dresden.de/files/Images/people/chair-cc/theses/2407_Rossel_MA.pdf)
- [ ] download lean-egg
- [ ] try it on the Filmus' domino proof
- [ ] try grind on Filmus' domino proof


### 2025-11-11
Meeting with Shachar. Discussion about Katamino, shachar wrote a Katamino
program in Z3 and got up to 7 shapes. Discussion about MathComp.
Shachar recommended I always have a project to work on, and have something I am
reading or learning.


## Reading List - things I want to read
- [Correctness of a compiler for arithmetic expressions in Lean | kqueue.org](https://kqueue.org/blog/2020/10/15/arithcc/)
- [2405.10188 Bridging Syntax and Semantics of Lean Expressions in E-Graphs](https://arxiv.org/abs/2405.10188)
- [GitHub - philzook58/awesome-egraphs: An awesome list of e-graph resources](https://github.com/philzook58/awesome-egraphs?tab=readme-ov-file#theorem-proving-and-verification)
- Learn about the `mvcgen` tactic
- Liquid Rust
- Theorem Proving in Lean
- Functional Programming in Lean - I stopped at
  monad-transformers/reader-io.html
- Meta-Programming in Lean - I stopped at Tactics



## Ideas for Later
- Separation Logic in Lean
- parser monad as a monad transformer
- compiling parser combinators or optimizing them
* Reading MathComp


## Working on
* latex-2-lean
* Project with Hila


## parser-monad
The parser monad is pretty much just what it sounds like, it's building up
parsers as functions from input that modify an input and return a value, and
treating them as a monad let's you construct them very easily.
