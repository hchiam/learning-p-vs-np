# Learning P vs NP problems

Just one of the things I'm learning. <https://github.com/hchiam/learning>

To oversimplify, P = easy, NP = hard.

**P** = theoretically _solvable_ in O(n^k) time. ["Easy" to solve](https://en.wikipedia.org/wiki/P_versus_NP_problem#Does_P_mean_%22easy%22?).

**NP** = theoretically _verifiable_ in O(n^k) time. "Easy" to verify. Example: Sudoku is in NP, but does not seem to be in P.

P ⊆ NP, but is P = NP? It seems so far that P ≠ NP.

In other words, "easy" problems can be "easy" to verify. But if a solution is "easy" to verify, is there always an "easy" way to solve the problem? It seems so far that there will always exist problems that are "harder" to solve than to verify.

Diagram from <https://en.wikipedia.org/wiki/P_versus_NP_problem> :

<img alt="diagram from Wikipedia article on P versus NP" title="diagram from Wikipedia article on P versus NP" src="https://upload.wikimedia.org/wikipedia/commons/a/a0/P_np_np-complete_np-hard.svg" height="200" data-licence-info="https://commons.wikimedia.org/wiki/File:P_np_np-complete_np-hard.svg">
