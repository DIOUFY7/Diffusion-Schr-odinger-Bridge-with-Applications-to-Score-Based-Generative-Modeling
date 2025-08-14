# Diffusion-SchrÖdinger-Bridge-with-Applications-to-Score-Based-Generative-Modeling
Generative modeling as a Schrödinger bridge problem is a famous entropy regularized Optimal Transport (OT) problem introduced by Schr¨odinger (1932). 
Given a reference diffusion with finite time horizon T, a data distribution and a prior distribution, solving the SB amounts to finding the closest diffusion to the reference (in terms of Kullback–Leibler divergence on path spaces) which admits the data distribution as marginal at time t = 0 and the prior at time t = T.

The reverse-time diffusion solving this SB problem provides a new Score-Based Generative Modeling (SGM) algorithm which enables approximate sample generation from the data distribution using shorter time intervals compared to the original SGM methods.
