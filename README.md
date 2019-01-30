# Population Biology

This is a short (3-week) graduate course on population biology.
We will cover mathematical and computational modeling of "populations"
(of organisms, genotypes, molecules, etcetera).
The main goal of the course is to give you the tools to
read and interpret models found in the literature,
and to get a start on creating your own models.
We'll create and visualize random and deterministic (nonrandom) models,
and show how to move from one to the other.
We'll learn how to understand the short- and long-term behavior of systems,
categorizing stable points and periodic orbits.
Along the way we'll cover 
some aspects of probability (means, variances, a few distributions) and simulation,
as well as some linear algebra (matrix products, changes of basis, eigenvalues and eigenvectors).

**Reading:** 
A good reference would be *A Biologist's Guide to Mathematical Modeling in Ecology and Evolution*, by Sarah P. Otto and Troy Day.
We'll cover a lot of things in this book - and, it has great background on the math we use - but not in the same order.

**Software:**
We'll do a lot of work (simulation, plotting) in jupyter notebooks.
Towards the end we'll also start using the individual-based simulator [SLiM](https://messerlab.org/slim/),
which takes care of a lot of messy details for us.

**Jupyter notebooks:**
You can find these in [notebooks/](notebooks/).

## Schedule:

Day 1 (Wednesday, 1/30) - individual-based models

: Building and visualizing individual-based models; finding means and variances;
    differential equation limits.
    Example: exponential, logistic population growth.

    - [notebook](notebooks/lecture_01.ipynb)

Day 2 (Friday, 2/1) - taking the limit

: Building and visualizing individual-based models: more variables.
    Example: predator-prey models.

Day 3 (Monday, 2/4) - behaviors of one-dimensional systems

: The (deterministic) logistic model: stability, cycles, and chaos.

Day 4 (Wednesday, 2/6) - not everyone is the same

: Linear algebra to concisely describe stage-structured linear population models.

Day 5 (Friday, 2/9) - eigenpopulations

: Linear algebra for linear models: using eigenvalues and eigenvectors to completely
    understand stage-structured population models.

Day 6 (Monday, 2/12) - local analysis

: General behaviors for more-than-one-dimensional systems:
    using locally linear approximations to understand
    the local behavior of systems.

Day 7 (Wednesday, 2/14) - equilibria and stability

: Using information about fixed points to understand long-term behavior.

Day 8 (Wednesday, 2/14) - adding back randomness

: What does the behavior of a deterministic model tell you about the random model
    that it's approximating? Simulation and heuristic methods.

Day 9 (Friday, 2/16) - spatial models in SLiM

: How to implement a spatial model in [SLiM](https://messerlab.org/slim/).

Day 10 (Monday, 2/19) - range expansions

: Translating what we know about nonspatial systems
    to construct a two-population spatial model
    of invasion and coexistence.
