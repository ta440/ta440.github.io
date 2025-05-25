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

Divergence and vorticity damping are explicit diffusion mechanisms used in dynamical cores to ensure numerical stability. There is a mesh-dependent upper bound on the corresponding diffusion coefficient, else the diffusion itself becomes a source of instability. This work considers such stability limits for three gnomonic cubed-sphere meshes -- 1) equidistant, 2) equiangular, and 3) equi-edge mappings. Von Neumann analysis is used to derive linear stability limits, which show that the stability of divergence and vorticity damping depends on the cell areas and aspect ratios of the cubed-sphere grid. The linear theory is compared to practical divergence and vorticity damping limits in the CAM-FV3 dynamical core, using a baroclinic wave test case on the equiangular and equi-edge grids. For divergence damping, both the magnitude of maximum stable coefficients and the locations of instability agree with linear theory. Due to implicit vorticity diffusion from the transport scheme, practical limits for vorticity damping are lower than the explicit stability limits. The maximum allowable vorticity damping coefficient varies with the choice of horizontal transport scheme for the equi-edge grid; it is hypothesised that this indicates the relative implicit diffusion of the transport scheme in this test.
