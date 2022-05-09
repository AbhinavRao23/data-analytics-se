(advanced-methods)=
# Advanced Methods for Characterizing Posteriors

In this chapter, we discuss techniques that enable us to characterize the posterior in Bayesian inference problems that do not have an analytical solution. First, we cover sampling methods and, in particular, Markov Chain Monte Carlo and sequential Monte Carlo. These methods generate samples from the posterior of interest without the need to know it analytically. Second, we study variational inference methods which seek to approximate the posterior within a parameterized class of distributions. In both cases, we emphasize the use of probabilistic programming software for practical implementation.