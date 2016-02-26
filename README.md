# Interactive Markov-chain Monte Carlo
![NUTS in action](https://raw.githubusercontent.com/chi-feng/mcmc-demo/master/docs/nuts.gif)

## List of algorithms
 - [Random Walk Metropolis Hastings](RandomWalkMH.js)
 - [Adaptive Metropolis Hastings](AdaptiveMH.js) \[1\]
 - [Hamiltonian Monte Carlo](HamiltonianMC.js) \[2\] (Algorithm 1)
 - [No-U-Turn Sampler (Naive)](NaiveNUTS.js) \[2\] (Algorithm 2)
 - [Metropolis-adjusted Langevin Algorithm (MALA)](MALA.js) \[3\]
 - [Hessian-Hamiltonian Monte Carlo (H2MC)](algorithms/H2MC.js) \[4\]

\[1\] H. Haario, E. Saksman, and J. Tamminen, [An adaptive Metropolis algorithm](http://projecteuclid.org/euclid.bj/1080222083) (2001)  
\[2\] M. D. Hoffman, A. Gelman, [The No-U-Turn Sampler: Adaptively Setting Path Lengths in Hamiltonian Monte Carlo](http://arxiv.org/abs/1111.4246) (2011)  
\[3\] G. O. Roberts, R. L. Tweedie, [Exponential Convergence of Langevin Distributions and Their Discrete Approximations](http://www2.stat.duke.edu/~scs/Courses/Stat376/Papers/Langevin/RobertsTweedieBernoulli1996.pdf) (1996)  
\[4\] Li, Tzu-Mao, et al. [Anisotropic Gaussian mutations for metropolis light transport through Hessian-Hamiltonian dynamics](https://people.csail.mit.edu/tzumao/h2mc/). ACM Transactions on Graphics (TOG) 34.6 (2015): 209.


