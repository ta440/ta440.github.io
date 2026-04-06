---
title: "A conservative, discontinuous Galerkin, tracer transport scheme using compatible finite elements"
collection: publications
category: preprints
permalink: /publication/2026-03-19_paper_three
excerpt: 'This paper describes and tests a conservative transport scheme for scalar tracers using compatible finite elements.'
date: 2026-03-19
venue: 'false'
paperurl: 'https://arxiv.org/abs/2603.19075'
---

Abstract: This paper outlines a conservative transport scheme for scalar tracers within a compatible finite element model for geophysical fluid equations. Instead of using the advective transport equation for a mixing ratio, a conservative transport  equation is solved for the tracer density of the mixing ratio multiplied by the dry density. This ensures mass conservation in the continuous equations, which can be preserved in the discrete equations with a discontinuous Galerkin transport scheme. Our method is designed to work for two placements of the mixing ratio in a Charney-Phillips vertical staggering: either co-located with the dry density or vertically staggered from it. The new scheme is designed to conserve the tracer density and ensure consistency by maintaining a constant mixing ratio. Additionally, a mass-conserving limiter is developed to ensure non-negativity in the co-located configuration. Tests with terminator toy chemistry and a moist rising bubble show the use of the new transport scheme with physics terms and its ability to accurately model mass conservation of moisture species in a dynamical core setup.
