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

Day 1 (Monday, 2/22) - individual-based models

: Building and visualizing individual-based models; finding means and variances;
    differential equation limits.
    Example: exponential, logistic population growth.

- [notebook](notebooks/individual_models.ipynb)

Day 2 (Wednesday, 2/24) - taking the limit with one-dimensional systems

: The (deterministic) logistic model: stability, cycles, and chaos.

- (continued from Day 1)

Day 3 (Friday, 2/26) - Differential equations, and higher dimensions

: Building and visualizing individual-based models: more variables.
    Example: Lotka-Volterra dynamics

- [notebook](notebooks/diff_eqns.ipynb)

Day 4 (Monday, 3/1) - multidimensional model building

: Isoclines, and more on building multidimensional models.
    Example: SI (susceptible-infected) models.

- [notebook](notebooks/species_interactions.ipynb)

Day 5 (Wednesday, 3/3) - the SI model, and intro to stage-structured models

: Building a SI model, introduction to juvenile-adult model.

Day 6 (Friday, 3/5) - linear algebra and stage-structured models.

: Linear algebra to concisely describe stage-structured linear population models;
    using eigenvalues and eigenvectors to completely
    understand stage-structured population models.

Day 7 (Monday, 3/8) - local analysis; equilibria and stability

: Using information about fixed points to understand long-term behavior.
    General behaviors for more-than-one-dimensional systems:
    using locally linear approximations to understand
    the local behavior of systems.

Day 8 (Wednesday, 3/10) - Modeling in SLiM

: How to use [SLiM](https://messerlab.org/slim/) for simulations.

Day 9 (Friday, 3/12) - spatial demographics

: How to implement a spatial model in SLiM.

Extra topic (perhaps merged above) - species interactions

: Species interactions in SLiM: predator-prey models

[Here](notebooks/2019/schedule_2019.html) are notebooks from a previous time this course was taught.

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

