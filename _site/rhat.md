# Rhat or the Gelman-Rubin diagnostic

The Rhat diagnostic was first introduced in [^1], but the version presented here is the one discussed in [^2]. Put simply, it accounts for between chain variance and within chain variance to produce a single number (Rhat). An algorithm such as <a href="demc">Differential Evolution Markov Chain</a> is thought to have converged when Rhat is close to 1 or Rhat<1.1.

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

~~~matlab
<pending>
~~~

[^1]: Gelman, Andrew, and Donald B. Rubin. “Inference from Iterative Simulation Using Multiple Sequences.” Statistical Science, vol. 7, no. 4, 1992, pp. 457–472. JSTOR, JSTOR, <www.jstor.org/stable/2246093>.
[^2]: Gelman, A., Carlin, J., Stern, H., Dunson, D., & Vehtari, A. (2013). Bayesian data analysis (3rd ed.). Taylor & Francis.