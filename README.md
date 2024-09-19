# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

Definition of big O

$f(n)\in O(g(n)) \iff \exists c>0, \exists n_0, \forall n\ge n_0: f(n) \leq c g(n)$

For any c > 0 there is a $n_0$ so that $n \leq n_0$  so $f(n)<c⋅g(n)$
Then for O(g(n)) there is a specific c and $n_0$ such that $f(n)\leq c⋅g(n)$

So $f(n)\in o(g(n)) ==> f(n)\in O(g(n))$


“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
