# MATH 5110 Applied Linear Algebra and Matrix Analysis

## Linear Algebra for the AI Age: Geometry, Computation, and Data

**Book website:** [https://wanghemath.github.io/MATH5110Book/](https://wanghemath.github.io/MATH5110Book/)

This repository contains the online interactive book for **MATH 5110: Applied Linear Algebra and Matrix Analysis**.

This book is an applied, story-driven introduction to **linear algebra and matrix analysis** for graduate students in **[MS Applied Mathematics](https://graduate.northeastern.edu/programs/ms-applied-mathematics/master-of-science-in-applied-mathematics/)** and **[MS Statistics](https://graduate.northeastern.edu/programs/ms-statistics/master-of-science-in-statistics/)** at **Northeastern University**. It begins with the concrete problem of solving linear equations, then gradually uncovers the deeper structures behind the computations: vector spaces, linear transformations, bases, coordinates, eigenvectors, inner products, projections, factorizations, spectral theory, and modern applications in data science and AI.

The guiding idea is:

> Linear algebra is the language of structure, computation, geometry, data, and modern intelligent systems.

---


## What makes this book different

This is not a traditional textbook that only teaches procedures.

It is designed as a **guided mathematical journey** from ordinary vectors and systems of equations to modern data, computation, networks, signal processing, optimization, probability, and AI.

The book moves back and forth among four viewpoints:

1. **Algebraic:** equations, matrices, subspaces, transformations, determinants, eigenvalues.
2. **Geometric:** dimension, coordinates, orthogonality, projections, distance, angles.
3. **Computational:** row reduction, LU, QR, Schur, SVD, FFT, sparse matrices, algorithms.
4. **Applied/data-driven:** least squares, compression, PCA, Markov chains, graph networks, optimization, probability, and AI.

A vector is treated not only as a list of numbers, but also as a direction, a data point, a signal, a function, or an embedding.

A matrix is treated not only as a rectangular array, but also as a transformation, an algorithm, a model, a projection, a graph operator, or a layer in a neural network.

A decomposition is treated not only as a formula, but as a way to reveal hidden structure.

---

## How to use this book

Each chapter is written as an independent learning unit. Most chapters include:

- a story-driven opening motivation;
- precise definitions, theorems, and examples;
- Python computations and numerical experiments;
- challenge questions;
- practice problems;
- hide/show proofs and solutions;
- AI companion activities for guided exploration.

Each lab is designed for independent study. Labs usually include:

- a Quarto lab page;
- an interactive HTML exploration;
- a Jupyter notebook for Python practice;
- conceptual questions;
- computational experiments;
- AI companion prompts.

The goal is for students not only to read mathematics, but to **interact with it**.

---

## Course learning arc

### Part I. The computational beginning

The course begins with the practical question:

> When does a system of linear equations have no solution, one solution, or infinitely many solutions?

This leads naturally to matrices, row operations, rank, null spaces, determinants, and matrix factorizations.

### Part II. The language of vector spaces

A linear system is not only a calculation. It reveals the deeper language of vector spaces:

- subspaces;
- span;
- linear independence;
- bases;
- dimension;
- coordinates;
- linear transformations;
- kernels and images;
- quotient spaces.

### Part III. Spectral structure

Eigenvalues and eigenvectors reveal directions that a transformation preserves. This leads to:

- diagonalization;
- Jordan canonical form;
- matrix powers;
- dynamical systems;
- Markov chains;
- Perron--Frobenius theory;
- PageRank-type ideas.

### Part IV. Geometry from inner products

Inner products give length, angle, distance, and orthogonality. This leads to:

- projections;
- Gram--Schmidt;
- QR factorization;
- least squares;
- adjoints;
- symmetric and Hermitian matrices;
- Schur decomposition;
- spectral decomposition;
- positive definiteness.

### Part V. Data, signals, networks, and applications

The later chapters show how the same core ideas power modern applications:

- SVD and PCA;
- image compression;
- Haar wavelets;
- FFT;
- Grassmannians;
- numerical eigenvalue computation;
- multilinear algebra;
- Hilbert spaces;
- topological data analysis;
- spectral graph theory;
- differential equations;
- optimization;
- probability;
- matrix calculus.

---

## Chapter roadmap

| Chapter | Topic | Main ideas |
|---:|---|---|
| 1 | Linear Systems | Linear systems, row reduction, existence and uniqueness |
| 2 | Matrix Algebra | Matrix products, inverses, transpose, LU, rank |
| 3 | Linear Spaces, Subspaces, Linear Maps | Vector spaces, span, direct sums, kernels, images, quotients |
| 4 | Basis, Dimension, Rank--Nullity | Bases, coordinates, dimension, rank--nullity |
| 5 | Coordinates, Matrices, Change of Basis | Coordinate vectors, matrix representations, similarity |
| 6 | Determinants | Area/volume, invertibility, row operations, characteristic polynomial |
| 7 | Eigenvalues and Diagonalization | Eigenvectors, eigenspaces, diagonalization, powers |
| 8 | Jordan Canonical Form | Generalized eigenvectors, Jordan blocks, Cayley--Hamilton |
| 9 | Dynamical Systems and Markov Chains | Linear iteration, stochastic matrices, Perron--Frobenius |
| 10 | Inner Products, Projections, QR, Adjoints | Geometry, orthogonality, Gram--Schmidt, QR |
| 11 | Complex Inner Products and Schur | Hermitian inner product, unitary matrices, Schur decomposition |
| 12 | Least Squares and Data Fitting | Normal equations, projections, regression, data fitting |
| 13 | Symmetric and Hermitian Matrices | Spectral theorem, quadratic forms, positive definiteness |
| 14 | Singular Value Decomposition | SVD, low-rank approximation, image compression, PCA |
| 15 | Haar Bases and Wavelets | Orthogonal bases, multiscale signals, compression |
| 16 | Fast Fourier Transforms | Fourier series, DFT, FFT, signals |
| 17 | Grassmannians and Subspace Distances | Principal angles, subspace geometry, data subspaces |
| 18 | Computational Complexity and Eigenvalues | Big-O, sparse matrices, power method, QR algorithm |
| 19 | Applications of Multilinear Algebra | Tensor products, exterior products, multilinear maps |
| 20 | Hilbert Spaces and Applications | Metric, normed, and inner product spaces; projection theorem |
| 21 | Topological Data Analysis | Chain complexes, homology, persistence, barcodes |
| 22 | Duality and Cohomology | Dual spaces, cochains, coboundaries, cohomology |
| 23 | Spectral Graph Theory | Graphs as matrices, Laplacian, spectrum, clustering |
| 24 | Linear Algebra and Differential Equations | Matrix exponential, systems of ODEs, stability |
| 25 | Linear Algebra and Optimization | Convexity, gradients, least squares, constraints |
| 26 | Linear Algebra and Probability | Random vectors, covariance, Gaussian distributions, random matrices |
| 27 | Matrix Calculus | Gradients, Hessians, Jacobians, optimization and machine learning |

---

## Conceptual map

The book is organized around a connected conceptual network:

```text
Sets and maps
   ↓
Algebraic structures
   ↓
Vector spaces and linear transformations
   ↓
Subspaces, sums, quotients
   ↓
Bases, coordinates, dimension
   ↓
Matrices, row operations, rank, LU, determinants
   ↓
Linear systems and computation
```

From there, the course branches into deeper themes:

```text
Eigenvalues and eigenspaces
   → diagonalization and Jordan form
   → dynamical systems, Markov chains, PageRank
   → spectral graph theory

Inner product spaces
   → orthogonal projection and orthogonal bases
   → least squares
   → QR and Schur
   → spectral theorem
   → SVD and PCA
   → FFT and wavelets
   → Hilbert spaces

Matrix computation
   → optimization
   → matrix calculus
   → random variables and covariance
   → probability and machine learning
```

---

## Mathematical habits for the course

The course repeatedly practices three habits.

### 1. Translate among representations

A single idea may appear as:

- an equation;
- a matrix;
- a linear map;
- a geometric object;
- a dataset;
- a computational algorithm.

For example, a linear transformation can be viewed as:

- a function \(T:V\to W\);
- a matrix \(A\) after choosing bases;
- a geometric machine acting on vectors;
- a data transformation acting on features;
- an operator whose structure is revealed by eigenvalues or singular values.

### 2. Ask the invariant question

Many computations depend on coordinates, but the important ideas are often invariant:

- dimension of a vector space;
- rank and nullity of a linear map;
- eigenvalues under similarity;
- singular values under orthogonal or unitary changes of coordinates;
- subspace angles on Grassmannians;
- connected components from Laplacian zero eigenvalues.

### 3. Connect proof and computation

A theorem is most useful when it becomes a computational tool:

- the rank--nullity theorem explains free variables;
- the spectral theorem explains quadratic forms and PCA;
- the projection theorem explains least squares;
- the SVD explains low-rank approximation;
- the Perron--Frobenius theorem explains long-term behavior of positive systems;
- the Laplacian quadratic form explains smoothness and clustering on graphs.

---

## Python preview

The book uses Python to verify theory, experiment with examples, and visualize structure.

For example:

```python
import numpy as np

A = np.array([[2, 1],
              [1, 2]], dtype=float)

w, V = np.linalg.eigh(A)

print("A =")
print(A)
print("Eigenvalues:", w)
print("Orthonormal eigenvectors:")
print(V)
print("Reconstruction error:",
      np.linalg.norm(A - V @ np.diag(w) @ V.T))
```

This small computation previews a central theme of the course: a symmetric matrix can be reconstructed from its eigenvalues and orthonormal eigenvectors.

---

## AI companion prompts

Use AI as a study partner, not as a replacement for mathematical reasoning.

Examples:

1. **Concept check:** Explain the difference between a matrix, a linear transformation, and a coordinate representation.
2. **Proof coach:** Give me hints for proving the rank--nullity theorem without giving the full solution first.
3. **Computation coach:** Generate a Python example where a matrix is diagonalizable and another where it is not.
4. **Application bridge:** Explain how projections lead to least squares, and how least squares leads to data fitting.
5. **Synthesis:** Make a concept map connecting QR, Schur, spectral decomposition, SVD, and PCA.

Students should verify AI-generated explanations with definitions, theorems, examples, and computation.

---

## Suggested independent-study routine

For each chapter:

1. Read the story and definitions.
2. Work through examples by hand.
3. Run the Python computations.
4. Try the interactive lab.
5. Complete the practice problems before opening solutions.
6. Ask an AI companion to generate one similar problem.
7. Solve the AI-generated problem independently.
8. Check the solution using Python or symbolic computation.
9. Write a short explanation in your own words.

---

## Interactive labs

  labs include:

- Linear Systems:interactive systems, rank, row reduction, and geometry.
- Matrix Algebra: matrix products, inverses, rank, transpose, Gram matrices, and LU factorization.
- vector spaces and subspaces;
- bases and coordinates;
- determinants;
- eigenvalues and diagonalization;
- Jordan canonical form;
- Markov chains and dynamical systems;
- projections and least squares;
- QR and Schur;
- symmetric matrices and spectral theorem;
- SVD and image compression;
- Haar wavelets;
- FFT;
- Grassmannians;
- computational complexity and eigenvalue computation;
- multilinear algebra;
- Hilbert spaces;
- topological data analysis;
- duality and cohomology;
- spectral graph theory;
- differential equations;
- optimization;
- probability;
- matrix calculus.

---

## Repository structure

A typical structure is:

```text
.
├── _quarto.yml
├── index.qmd
├── preface.qmd
├── math-5110-book-overview.qmd
├── chapters/
│   ├── chapter-01-linear-systems.qmd
│   ├── chapter-02-matrix-algebra.qmd
│   └── ...
├── labs/
│   ├── lab-01-linear-systems.qmd
│   ├── lab-01-interactive.html
│   ├── lab-01-linear-systems.ipynb
│   ├── lab-02-matrix-algebra.qmd
│   ├── lab-02-interactive.html
│   └── lab-02-matrix-algebra.ipynb
├── figures/
├── data/
├── docs/
└── README.md
```

The `docs/` folder is used for GitHub Pages when the Quarto project is configured with:

```yaml
project:
  type: book
  output-dir: docs
```

---

## Build the book locally

Install Quarto:

<https://quarto.org/>

Clone the repository:

```bash
git clone https://github.com/wanghemath/MATH5110Book.git
cd MATH5110Book
```

Render the book:

```bash
quarto render
```

Preview the book locally:

```bash
quarto preview
```

---

## Update and publish the book

After editing chapters or labs, render the book:

```bash
quarto render
```

Then commit and push:

```bash
git add .
git commit -m "Update book"
git push
```

If GitHub Pages is configured to serve from the `docs/` folder on the `main` branch, the website will update at:

[https://wanghemath.github.io/MATH5110Book/](https://wanghemath.github.io/MATH5110Book/)

---

## Suggested `_quarto.yml` structure

A simple version of the book configuration may look like:

```yaml
project:
  type: book
  output-dir: docs

book:
  title: "MATH 5110 Applied Linear Algebra and Matrix Analysis"
  subtitle: "Linear Algebra for the AI Age: Geometry, Computation, and Data"
  author: "He Wang"
  chapters:
    - index.qmd
    - preface.qmd
    - math-5110-book-overview.qmd
    - chapters/chapter-01-linear-systems.qmd
    - labs/lab-01-linear-systems.qmd
    - chapters/chapter-02-matrix-algebra.qmd
    - labs/lab-02-matrix-algebra.qmd

format:
  html:
    theme: cosmo
    toc: true
    number-sections: true
    code-fold: true
    code-tools: true
```

---

## References and further study

The course draws on standard references in applied and advanced linear algebra, matrix analysis, numerical linear algebra, optimization, probability, signal processing, graph theory, and machine learning.

Recommended references include works by:

- Stephen Boyd and Lieven Vandenberghe;
- Mark Gockenbach;
- Gilbert Strang;
- Thomas Shores;
- Peter Olver and Chehrzad Shakiban;
- Stephan Garcia and Roger Horn;
- Carl Meyer;
- Steven Roman;
- Jean Gallier and Jocelyn Quaintance.

---

## For students

When reading the book, ask:

- What is the mathematical object?
- What does it mean geometrically?
- What does it do computationally?
- What structure is being revealed?
- What is invariant under a change of coordinates?
- How can I verify the result with Python?
- How can I explain the idea without only using formulas?
- What can AI help with, and what must I still understand myself?

---

## Author

**He Wang**  
Department of Mathematics  
Northeastern University  

Course: **MATH 5110 Applied Linear Algebra and Matrix Analysis**

---

## License and use

This repository is intended for educational use. Unless otherwise noted, the teaching materials in this repository are licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

Please check the repository license before sharing, adapting, or reusing the material.
 
