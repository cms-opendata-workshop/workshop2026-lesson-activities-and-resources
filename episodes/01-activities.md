---
title: "Outreach and educational activities and resources"
teaching: 10
exercises: 2
editor_options: 
  markdown: 
    wrap: 72
---

::: questions
- What level are these activities for?
- What skills are needed for these activities?
- How can I deploy these activities for my students?
- Can I or my students go further than what is listed here?
:::

::: objectives
- Good questions
:::

## Particle physics playground

::: testimonial
- Intended audience
  - High school
  - Undergrad
- Learning goals
  - Python reinforcement
  - Relativistic kinematics reinforcement
- Necessary skills/background knowledge
  - Basic python
  - `pandas` (for some exercises)
  - Some awareness of relativistic kinematics
- Length of time to complete
  - 45-120 minutes (suggested HW assignment)

:::

In this activity, students will read in data representing the energy and
momentum of pairs of muons, recorded in collisions at the LHC with the
CMS detector. Students will calculate the mass of these muons using both
*classical physics* and *special relativity*.

This activity has been used with freshman in an introductory programming
class and an upper-level particle physics course. Introductory python
and exposure to the `matplotlib` and `pandas` libraries are sufficient.

Supplemental material is also provided for instructors who want to go
further with their students.

- [Particle Physics
  Playground](https://sites.google.com/siena.edu/particle-physics-playground/home)
- [Google
  Slides](https://docs.google.com/presentation/d/1JKwlRqiKnupkw9iir4d1YCL87ligSZz6STW_GQl73UI/edit?usp=sharing)
  Introduction to activity
- Colab notebooks
  - [Student
    version](https://colab.research.google.com/drive/1rzqu-NmFA-Pwc93fnLy5u4sNnvxzKyBS?usp=sharing)
  - [Instructor's
    version](https://colab.research.google.com/drive/1izsL2Ep-BD9PlTrJdWhtuwwMKkw-bVa6?usp=sharing)

### Supplemental materials

Depending on the level of students that you are working with and how
much scaffolding you want to provide, the following materials may be
helpful.

- Four-vector practice
  - [Google Doc of
    4-vectors](https://docs.google.com/document/d/1YsZYdswG5fe5CD3HxG10iVfTvxjSx5TJaB5TT0D8iiA/edit?usp=sharing)
    This document contains randomly generated 4-vectors that either have
    the same mass or come from the same parent particle. They can be
    printed out, cut up into strips, and passed out to students to
    calculate and compare.
  - [Colab notebook to generate
    4-vectors](https://colab.research.google.com/drive/10MNXFV7NTrCEULInNjBAxKf7gR0pGscp?usp=sharing)
    *This is very much a work in-progress so it might not be obvious how
    to use this. Let's make it better!*
- Particle lifetime activity / homework (python/Colab). This assignment
  asks students to look up the lifetimes of particles and calculate how
  far they move in the lab for different momenta. Students also make a
  plot of lifetime for particles, color-coded by the interaction that
  mediates their dominant decays.
  - [Student
    version](https://colab.research.google.com/drive/1RNMyr5sQxgfDx3QgEm-cDXuyD1jo4Wvu?usp=sharing)
  - [Instructor's
    version](https://colab.research.google.com/drive/1B0rxM07FsWBpjH8cAoRYAVff2iRD80Ls?usp=sharing)
- Sample lesson plan and supplemental slides.
  - [Lesson
    plan](https://docs.google.com/document/d/1vJMvjxbZXjVtIfBKvo4N-33aOl1eADVV9jy7lwRCsS4/edit?usp=sharing)
    Developed by Katie Salvatore.
  - [Slides (minimalist
    approach)](https://docs.google.com/presentation/d/11gguILlKBtRCSh9jgkhrBNCc0lOzYsK-JCr5iD0gz6c/edit?usp=sharing)
    Developed by Katie Salvatore.

## Quark Workbench

::: testimonial
- Intended audience
  - High school or university physics students
- Learning goals
  - How quarks are combined into bound states (mesons and baryons)
  - Allowed "color" combinations for quark bound states
  - Electric charges of quarks in different families
  - Electric charge options for different mesons and baryons
  - Changes in charge and color between particles and antiparticles
- Necessary skills/background knowledge
  - Electric charge
  - Basic knowledge about quarks as particles
  - Experience with jigsaw puzzles
- Length of time to complete
  - 20 mins

:::

These quark puzzles are a fun hands-on way for students to learn how
quarks work together to produce the particles they already know, like
protons and neutrons. Solving the puzzles shows students that only
certain color combinations are allowed for baryons and mesons. By
studying the puzzle pieces they can see the different electric charges
of up and charm quarks compared to down and strange quarks, and they can
see how electric charge and color change from particle to antiparticle.
Once they build some mesons or baryons they can see what electric
charges are possible for those particles.

- QuarkNet resource webpage:
  <https://quarknet.org/data-portfolio/activity/quark-workbench>.
  - Here you can find guides for using this activity and printable files
    (paper or 3D!).
  - HTML interaction version:
    <https://web.quarknet.org/activities/qwbench/puzzle5.html>
- GlowForge files for acrylic/wood physical puzzle:
  [https://drive.google.com/file/d/1IJTlWQNk3tPKv2NrN39k3LNHqyGndIDy/](https://drive.google.com/file/d/1IJTlWQNk3tPKv2NrN39k3LNHqyGndIDy/view?usp=sharing)
  - My student used the QuarkNet 3D printer STL files to produce these
    versions for GlowForge. The letters/info are set to "score" mode and
    the borders to "engrave" mode.
- Google Slides version:
  [https://docs.google.com/presentation/d/1dKGYb5wK5yDHbDe5X5NCt5p7CO3viMl7QsqrXbmDE20/](https://docs.google.com/presentation/d/1dKGYb5wK5yDHbDe5X5NCt5p7CO3viMl7QsqrXbmDE20/edit?usp=sharing)
  - For remote participation or extra credit homework assignments
    students can copy/paste/rotate/move digital puzzle pieces.

Workshop presentation slides:
<https://indico.cern.ch/event/1672496/contributions/7205877/attachments/3320507/5945531/ODWS2026_QuarkWorkbench.pdf>
These slides show the background information, workbench prompts, and
learning questions that I give my students in class.

## Particle Discovery Lab

::: testimonial
- Intended audience
  - University physics students studying Modern Physics
- Learning goals
  - Practical experience using relativistic energy and momentum
  - Correctly apply energy and momentum conservation principles
  - Learn to analyze large-scale physics data stored in arrays
  - Gain prociency in understanding histograms and Poisson-distributed
    data
  - Practice performing and evaluating polynomial fits
  - Learn strategies for removing indistinguishable background events
  - Apply knowledge of uncertainty propagation
  - Create high-quality visualizations of data
  - Learn more about the history of a particular meson or boson
- Necessary skills/background knowledge
  - Python or MATLAB programming experience (e.g., from a computational
    physics course or introduction to programming course)
  - Modern Physics course knowledge of relativistic kinematics and
    energy conservation
- Length of time to complete
  - 2+ hours
  - The length of time is configurable based on which topics are
    included. My students use about 6 hours over 3 lab periods to
    complete the entire activity as written.

:::

The particle discovery lab uses CMS dimuon data from 2016 published via
the CERN Open Data Portal. We have developed an undergraduate
intermediate-level lab exercise to complement the many high school-level
exercises available via the Open Data Portal. Student code is available
in both MATLAB and Python, and does not require special CMS Open Data
software. The goal of this exercise is to reconstruct decays of unknown
particle X (initial state) to 2 muons (final state). Students will use
histograms to display their calculated mass for particle X, and learn
about fitting and subtracting background contributions from data.
Uncertainty propagation concepts are included through each step of the
analysis. After isolating the signal distribution students will
determine which particle they have discovered and compare their observed
properties (mass and width) to the known properties.

- CERN Open Data Portal activity webpage:
  <https://opendata.cern.ch/record/49>
- Student-facing activity webpage:
  [https://quarknet.org/data-portfolio/activity/quark-workbench](https://bethel-physics.github.io/ParticleDiscoveryLab/).
- Instructor's github branch:
  <https://github.com/bethel-physics/ParticleDiscoveryLab/tree/instructors>
- Colab notebooks:
  - Students:
    [https://colab.research.google.com/drive/1aK6INkWrF_6mlDEYU4RxMYMhYm-8O7MF](https://colab.research.google.com/drive/1aK6INkWrF_6mlDEYU4RxMYMhYm-8O7MF?usp=sharing)
  - Instructors:
    [https://colab.research.google.com/drive/1O99rvGitbZ8RV6QZzvrsx8a3mL_Wu-wm](https://colab.research.google.com/drive/1O99rvGitbZ8RV6QZzvrsx8a3mL_Wu-wm?usp=sharing)

Workshop presentation slides:
<https://indico.cern.ch/event/1672496/contributions/7205877/attachments/3320507/5945532/ODWS2026_ParticleDiscoveryLab.pdf>

## Diumuon invariant mass spectrum from NANOAOD

*Exploring a NANOAOD dataset and making an invariant mass plot*

::: testimonial
- Intended audience
  - High school or university physics students
- Learning goals
  - How to load NANOAOD using uproot and awkward
  - How to make simple selections on events
  - How to calculate and plot invariant mass
- Necessary skills/background knowledge
  - Python in a jupyter environment
  - awkward arrays
  - Python plotting with matplotlib
  - invariant mass
- Length of time to complete
  - 20 mins

:::

- [Github
  repo](https://github.com/cms-opendata-workshop/workshop2026-lesson-dimuon-from-nanoaod)
- [Binder
  link](https://mybinder.org/v2/gh/cms-opendata-workshop/workshop2026-lesson-dimuon-from-nanoaod/HEAD)
- [Colab
  link](https://colab.research.google.com/github/cms-opendata-workshop/workshop2026-lesson-dimuon-from-nanoaod/blob/main/dimuon-nanoaod.ipynb)

## Visualizing NANOAOD in a Jupyter notebook

This is a lesson to show how to visualise NANOAOD data in a Jupyter notebook.

::: testimonial
- Intended audience
  - High school or university physics students
- Learning goals
  - How to visualize individual NANOAOD events in a jupyter notebook
- Necessary skills/background knowledge
  - Python in a jupyter environment
- Length of time to complete
  - 15 mins

:::

- [Github
  page](https://github.com/cms-opendata-workshop/workshop2026-lesson-nanoaod-visualisation)
- [Binder](https://mybinder.org/v2/gh/cms-opendata-workshop/workshop2026-lesson-nanoaod-visualisation/HEAD?urlpath=%2Fdoc%2Ftree%2Fworkshop2026-ispynanoaod.ipynb)
- [Colab](https://colab.research.google.com/github/cms-opendata-workshop/workshop2026-lesson-nanoaod-visualisation/blob/master/workshop2026-ispynanoaod.ipynb)

## Maching Learning in Particle Physics

*Building a Simplified Particle Transformer for CMS Jet Classification*

::: testimonial
- Intended audience
  - Undergraduate students
  - Advanced high schoolers with some Python and linear algebra exposure
    can follow, but this is scoped as undergrad-level given the
    transformer architecture content
- Learning goals
  - Understand what a jet is and how a Higgs boson decaying to bb or cc
    shows up in CMS data
  - Learn how a transformer works from scratch (embeddings,
    self-attention, multi-head attention)
  - Build and train a simplified Particle Transformer (MiniParT) end to
    end in PyTorch on Google Colab
  - Evaluate a trained model using ROC curves and AUC, and see where the
    physics makes classification genuinely hard
- Necessary skills/background knowledge
  - Basic Python (variables, functions, loops)
  - General familiarity with the idea of machine learning, no prior
    neural network or transformer experience needed
  - A Google account for Colab
- Length of time to complete
  - 2 to 3 hours

:::

This lesson builds, from scratch, a small transformer model, MiniParT,
in PyTorch, that classifies pairs of jets from CMS Open Data as coming
from a Higgs boson decaying to two bottom quarks (Hbb), a Higgs boson
decaying to two charm quarks (Hcc), or ordinary QCD background. MiniParT
is a scaled down version of the Particle Transformer used in real CMS
physics analyses, small enough to train in minutes on a free Colab
session, but built on the same architecture ideas as the full size
model.

- [Lesson
  webpage](https://cms-opendata-workshop.github.io/workshop2026-lesson-minipart/index.html)
- [Google
  Slides](https://docs.google.com/presentation/d/1VpzyGB5RC7H1AIULSVKxc82TsBFVA6G-iJT_djkx3nY/edit?usp=sharing)

::: keypoints
- There are lots of good activities that you can use as-is
- All of these lessons allow you to make a copy and edit to work best
  for your class
- The facilitators are here to help you learn to use these materials
:::
