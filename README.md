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

**Instructor:**
Peter Ralph (plr@uoregon.edu) -- office hours as discussed in class
or by appointment, 270 Onyx Bridge.

## Schedule:

Day 1 (Wednesday, 1/30) - individual-based models

: Building and visualizing individual-based models; finding means and variances;
    differential equation limits.
    Example: exponential, logistic population growth.

    - [notebook](notebooks/lecture_01.ipynb)

Day 2 (Friday, 2/1) - taking the limit with one-dimensional systems

: The (deterministic) logistic model: stability, cycles, and chaos.

    - [notebook](notebooks/lecture_01.ipynb) (continued from before)

Day 3 (Monday, 2/4) - Differential equations, and higher dimensions

: Building and visualizing individual-based models: more variables.
    Example: Lotka-Volterra dynamics

    - [notebook](notebooks/lecture_02.ipynb)

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

## Prerequisites:

None, but students should be comfortable with algebra and the basics of calculus,
and either have some experience with programming or be ready to jump in with both feet.

## Inclusion and accessibility

I would like to know your preferred pronouns and name,
especially if it differs from the class roster.
I take seriously my responsibility to create inclusive learning environments.
Please notify me if there are aspects of the instruction or design of this
course that result in barriers to your participation! You are also encouraged
to contact the Accessible Education Center in 164 Oregon Hall at 541-346-1155
or uoaec@uoregon.edu.

I am committed to making our classroom an inclusive and respectful learning space.
Being respectful includes using preferred pronouns for your classmates.
Your classmates come from a diverse set of backgrounds and experiences;
please avoid assumptions or stereotypes, and aim for inclusivity.
Let us know if there are classroom dynamics that impede your (or someone else’s) full engagement. 

Please see [this page](policies.html) for more information on
campus resources, academic integrity, discrimination, and harassment (and reporting of it).

