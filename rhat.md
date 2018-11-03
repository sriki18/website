---
title: $$\hat{R}$$ (or the Gelman-Rubin diagnostic)
---

The $$\hat{R}$$ diagnostic was first introduced in [^1], but the version presented here is the one discussed in [^2]. Put simply, it accounts for between chain variance and within chain variance to produce a single number ($$\hat{R}$$). An algorithm such as <a href="demc">Differential Evolution Markov Chain</a> is thought to have converged when $$\hat{R}$$ is close to 1 or $$\hat{R}<1.1$$.

~~~matlab
<pending>
~~~

[^1]: Gelman, Andrew, and Donald B. Rubin. “Inference from Iterative Simulation Using Multiple Sequences.” Statistical Science, vol. 7, no. 4, 1992, pp. 457–472. JSTOR, JSTOR, <www.jstor.org/stable/2246093>.
[^2]: Gelman, A., Carlin, J., Stern, H., Dunson, D., & Vehtari, A. (2013). Bayesian data analysis (3rd ed.). Taylor & Francis.