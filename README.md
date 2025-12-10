# Tower of Hanoi - Mathematical Analysis and Optimisation

This repository contains a detailed mathematical study of the Tower of Hanoi puzzle, with a focus on optimisation in the multi-peg setting. The central component is a full exposition of the four-peg problem (Révé’s Puzzle) and Thierry Bousch’s 2014 proof establishing the optimality of the Frame-Stewart algorithm in this case.

The main document in this repository is:

**`Tower of Hanoi Optimisation Proof-1.pdf`**  
A 46-page research-style write-up exploring the theory, structure, and optimality properties of the puzzle.

---

## Contents

### `Tower of Hanoi Optimisation Proof-1.pdf`
A comprehensive project covering:

- **Introduction and motivation**  
  Historical background, classical variants, and the combinatorial structure of the puzzle.

- **Three-peg Tower of Hanoi**  
  Derivation of the optimal solution $T_N = 2^N - 1$ and discussion of shortest-path arguments using Hanoi graphs.

- **Hanoi graphs**  
  Graph representations of legal configurations, the recursive self-similar structure, and connections to the Sierpiński triangle.

- **The Frame-Stewart conjecture**  
  Statement of the conjecture, intuition behind the recursive strategy, known bounds, and structural heuristics.

- **Bousch’s 2014 proof of optimality for 4 pegs**  
  A structured and accessible exposition of:
  - the triangular-root functions $\Delta_n$ and $\nabla_n$  
  - the cost function $\Phi(N)$  
  - the auxiliary function $\Psi$ and its role in the argument  
  - the decomposition into critical cases  
  - the final step showing that the Frame-Stewart algorithm gives the minimal number of moves for 4 pegs

The document is self-contained and follows the structure of Bousch’s work while remaining accessible to a reader familiar with discrete mathematics.

---

## Project Goals

This repository aims to:

1. Present a rigorous mathematical treatment of the Tower of Hanoi puzzle.  
2. Provide a clear and structured exposition of Bousch’s optimality proof for the four-peg problem.  
3. Demonstrate advanced mathematical reasoning and proof-writing suitable for academic or technical evaluation.

---

## How to Use This Repository

- Open the PDF to read the full analysis.  
- The project is purely mathematical and contains no executable code.  
- The exposition is written to be readable independently of the original paper, but follows it closely.

---

## References

All relevant references, including the original paper by Thierry Bousch and standard texts on the Tower of Hanoi, are cited within the PDF.
