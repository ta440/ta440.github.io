---
title: "Stability analyses of divergence and vorticity damping on gnomonic cubed-sphere grids"
collection: publications
category: articles
permalink: /publication/2026-07-01_paper_five
excerpt: 'This paper derives linear stability limits to divergence and vorticity damping on gnomonic cubed-sphere grids. The linear theory is then applied to baroclinic wave simulations using the finite-volume cubed (FV3) dynamical core.'
date: 2026-07-01
venue: 'false'
paperurl: 'https://journals.ametsoc.org/view/journals/mwre/154/7/MWR-D-25-0192.1.xml'
---

Abstract:

Divergence and vorticity damping, which operate upon horizontal divergence and relative vorticity, are explicit diffusion mechanisms used in dynamical cores to ensure stability. To avoid numerical blowup from excessively strong diffusion, there are mesh-dependent upper bounds on the coefficients of the diffusion operators. This work considers such stability limits for three gnomonic cubed-sphere meshes: the 1) equidistant, 2) equiangular, and 3) equi-edge mappings. Stability limits are derived from a von Neumann analysis of damping with a simplified pseudo-Laplacian operator, as used in NOAA Geophysical Fluid Dynamics Laboratory’s (GFDL) finite-volume dynamical core on the cubed sphere (FV3), and with the full curvilinear Laplacian. The resulting stability limits depend on the gnomonic mapping through the cubed-sphere cell areas, aspect ratios, and grid nonorthogonality. The analytical stability limits are compared to practical divergence and vorticity damping upper bounds in FV3, using idealized tests and the equiangular and equi-edge grids. For divergence damping, both the magnitude of the maximum stable coefficients and the locations of instability agree with linear theory. Due to implicit vorticity diffusion in the FV3 transport scheme, practical limits for vorticity damping are lower than the explicit stability limits and depend on the choice of horizontal transport scheme.
