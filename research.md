Hopefully, this will be the last file I open for remembering what Shachar and I
discussed.

Here I write things a work log of what I did and summaries of meetings.

2025-12-02
I should leave the monads behind for now and focus on making Lean better for
maths and proofs. For next week:
- [ ] read the test cases section in
      [this paper](https://steuwer.info/files/publications/2026/POPL-Lean-Egg.pdf)
- [ ] read the evaluation section in
      [this paper](https://cfaed.tu-dresden.de/files/Images/people/chair-cc/theses/2407_Rossel_MA.pdf)
- [ ] download lean-egg
- [ ] try it on the Filmus' domino proof
- [ ] try grind on Filmus' domino proof


2025-11-11
Meeting with Shachar. Discussion about Katamino, shachar wrote a Katamino
program in Z3 and got up to 7 shapes. Discussion about MathComp.
Shachar recommended I always have a project to work on, and have something I am
reading or learning.


## Working on
* lean-boards
* parser-monad
* parser-combinator
* latex-2-lean
* Reading MathComp
* Project with Hila


# parser-monad
The parser monad is pretty much just what it sounds like, it's building up
parsers as functions from input that modify an input and return a value, and
treating them as a monad let's you construct them very easily.
