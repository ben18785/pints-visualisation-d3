## Samplers

* Exact (asymptotically)
  * Markov chain Monte Carlo
    * Gradient-free
      * Single chain
        * Adaptive
          * Adaptive covariance Metropolis
            * Remi
          * Delayed Rejection Adaptive Metropolis (DRAM)
          * Covariance adaptive slice sampler
          * Step-out slice sampler with overrelaxation
          * Doubling slice sampler with overrelaxation
          * Generalised elliptic slice sampler
        * Non-adaptive
          * Random Walk Metropolis
      * Multiple chains
        * Differential evolution
          * (Vanilla) differential evolution
          * Emcee hammer
          * DiffeRential Evolution Adaptive Metropolis (DREAM)
        * Population MCMC
    * Use gradients
      * 1st order sensitivity
        * Hamiltonian Monte Carlo (HMC)
        * No U-Turn Sampler (NUTS)
        * Metropolis Adjusted Langevin Algorithm (MALA)
      * 2nd order sensitivity
        * Riemannian Manifold HMC
        * Riemannian Manifold MALA
  * Nested
    * Gradient-free
      * Rejection nested sampler
      * Ellipsoidal nested sampler
      * MultiNest
      * Diffusive nested sampler
      * Dynamic nested sampler
      * PolyChord
      * dyPolyChord
    * Use gradients
      * Galilean Monte Carlo
  * Particle
    * SMC
* Approximate
  * Approximate simulation
    * Lazy ABC
  * Exact simulation
    * Rejection ABC
    * MCMC ABC
    * SMC ABC
    * Regression correction ABC