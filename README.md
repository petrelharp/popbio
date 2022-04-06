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

Day 1 (Friday, 1/27) - individual-based models

: Building and visualizing individual-based models; finding means and variances;
    differential equation limits.
    Example: exponential, logistic population growth.

- [notebook](notebooks/individual_models.ipynb)
- [html](notebooks/individual_models.html)

Day 2 (Monday, 1/31) - taking the limit with one-dimensional systems

: The (deterministic) logistic model: stability, cycles, and chaos.

- (continued from Day 1)

Day 3 (Wednesday, 2/2) - Differential equations, and higher dimensions

: Building and visualizing individual-based models: more variables.
    Example: Lotka-Volterra dynamics

- [notebook](notebooks/diff_eqns.ipynb)
- [html](notebooks/diff_eqns.html)

Day 4 (Friday, 2/4) - multidimensional model building

: Isoclines, and more on building multidimensional models.
    Example: SI (susceptible-infected) models.

- [notebook](notebooks/species_interactions.ipynb)
- [html](notebooks/species_interactions.html)

Day 5 (Monday, 2/7) - More on species interactions

: Building a SI model, introduction to juvenile-adult model.

- (continued from Day 4 and:)

Day 6 (Wednesday, 2/9) - linear algebra and stage-structured models.

: Linear algebra to concisely describe stage-structured linear population models;

- [notebook](notebooks/structured_populations.ipynb)
- [html](notebooks/structured_populations.html)

Day 7 (Friday, 2/11) - eigenanalysis of populations

: Using eigenvalues and eigenvectors to
    understand stage-structured population models.

- (continued from Day 6)

Day 8 (Monday, 2/14) - local analysis; equilibria and stability

: Using information about fixed points to understand long-term behavior.
    General behaviors for more-than-one-dimensional systems:
    using locally linear approximations to understand
    the local behavior of systems.

- [notebook](notebooks/nonlinear_systems.ipynb)
- [html](notebooks/nonlinear_systems.html)

Day 9 (Wednesday, 2/14) - Modeling in SLiM

: A quick introduction to [SLiM](https://messerlab.org/slim/) for simulations.

- [notebook](notebooks/slim_intro.ipynb)
- [html](notebooks/slim_intro.html)

## Prerequisites:

None, but students should be comfortable with algebra and the basics of calculus,
and either have some experience with programming or be ready to jump in with both feet.

## Inclusion and accessibility

I would like to know your pronouns and name,
especially if it differs from the class roster.
I take seriously my responsibility to create inclusive learning environments.
Please notify me if there are aspects of the instruction or design of this
course that result in barriers to your participation! You are also encouraged
to contact the Accessible Education Center in 164 Oregon Hall at 541-346-1155
or uoaec@uoregon.edu.

I am committed to making our classroom an inclusive and respectful learning space.
Your classmates come from a diverse set of backgrounds and experiences;
please avoid assumptions or stereotypes, and aim for inclusivity.
Let us know if there are classroom dynamics that impede your (or someone else’s) full engagement. 

Please see [this page](policies.html) for more information on
campus resources, academic integrity, discrimination, and harassment (and reporting of it).

