In this repository you will find the mathematica notebooks used to do the analyses and the figures for the manuscript "The coevolution of cooperation and socially-mediated
dispersal". They are numbered in order, with:
  1. General_Analyses.nb, the notebook used to compute the invasion analyses in section 3.1
  2. No_Equilibrium_Linear.nb, the notebook used to show that there is no singular strategy when we assume that the benefits from the public good are linear (section 3.2)
  3. Deterministic_Evolutionary_dynamics_linear.nb, the notebook used to compute the evolutionary trajectory of the population when the benefits from the public good are linear (section 3.2)
  4. Unstable_Equilibrium_Accelerating.nb, the notebook used to compute the singular strategies when we assume that the benefits from the public good are accelerating. We also show that the singular strategies are convergence unstable  (section 3.3)
  5. Deterministic_Evolutionary_dynamics_Accelerating.nb, the notebook used to compute the evolutionary trajectory of the population when the benefits from the public good are accelerating (section 3.3)
  6. Stable_Equilibrium_Accelerating.nb, the notebook used to compute the singular strategies when we assume that the benefits from the public good are accelerating. We also show that the singular strategies are convergence stable and can be evolutionary stable or unstable  (section 3.4)
  7. individual-based_simulations.jl, the julia script used to run most individual-based simulations (section 3.4)
  8. individual-based_simulations_correlations_in_mutations.jl, the julia script used to check whether correlation in mutation size between dispersal traits could still lead to transition between fully cooperative and fully defective populations, when population size is small and can drift (last paragraph of section 3.2, Fig S6).
  9. individual-based_simulations_focal_action.jl, the julia script used to run simulations where offspring dispersal did not only depend on the number of cooperators in a group but also on the focal individual previous action (Fig. S9).
