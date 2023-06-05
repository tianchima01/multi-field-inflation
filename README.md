# multi-field-inflation
Mathematica notebooks for modeling multi-field dynamics in inflationary cosmology. For each model, we solve the coupled ODEs describing the background evolution of multiple scalar fields, i.e. particle species, in the early universe.

Each notebook allows for an arbitrary field-space geometry, i.e. momentum-dependent coupling between the different scalar fields. The notebook test_solver_BCH uses a model inspired by arXiv:2012.05821 and implements a trajectory-smoothing feature to understand the solution to the background evolution ODEs pseudo-analytically.

/eigenvec-alignment/ contains a notebook that computes second-order perturbative corrections to the scalar field velocities in the aligned Hessian approximation. See arXiv:2010.15933 for details - the approximation casts the background field ODEs as matrix equations that can be solved via a perturbative expansion. This holds when the scalar potential's gradient is approximately an eigenvector of the potential's Hessian matrix. Heuristically, the perturbative expansion parameter is the misalignment angle between the normalized gradient and normalized "closest" eigenvector.
