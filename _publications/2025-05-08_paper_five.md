
---
title: "Stability analyses of divergence and vorticity damping on gnomonic cubed-sphere grids"
collection: publications
category: preprints
permalink: /publication/2025-05-08_paper_five
excerpt: 'This paper derives linear stability limits to divergence and vorticity damping on gnomonic cubed-sphere grids. The linear theory is then applied to baroclinic wave simulations using the finite-volume cubed (FV3) dynamical core.'
date: 2025-05-08
venue: 'false'
paperurl: 'https://arxiv.org/abs/2505.05624'
---

Abstract:

For simulations of time evolution problems, such as weather and climate models, taking the largest stable timestep is advantageous for reducing wall-clock time. A drawback of doing so is the potential reduction in nonlinear accuracy of the numerical solution - we investigate this for the Rotating Shallow Water Equations (RSWEs) on an f-plane. First, we examine how linear dispersion errors can impact the nonlinear dynamics. By deriving an alternate time evolution equation for the RSWEs, the dynamics can be expressed through interactions of three linear waves in triads. Linear dispersion errors may appear in the numerical representation of the frequency of each triad, which will impact the timestepped nonlinear dynamics. A new triadic error quantifies this by composing three stability polynomials from the oscillatory Dahlquist test equation. Second, we design two new test cases to examine the effect of timestep size in a numerical model. These tests investigate how well a timestepper replicates slow nonlinear dynamics amidst fast linear oscillations. The first test case of a Gaussian height perturbation contains a nonlinear phase shift that can be missed with a large timestep. The second set of triadic test cases excite a few linear waves to instigate specific triadic interactions. Two triadic cases are examined: one with a dominant directly resonant triad and another with near-resonances that redistribute fast mode energy into rings in spectral space. Three numerical models, including LFRic from the Met Office, are examined in these test cases with different timesteppers.
