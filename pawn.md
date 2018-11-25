---
title: PAWN
---

# PAWN

PAWN is a global sensitivity analysis (GSA) algorithm [^1]. Unlike variance based GSA approaches, it considers the entire distribution (specifically the CDF) of the model output. I have implemented PAWN and the first example discussed in [^1] in MATLAB. The latest code can be downloaded off the [MATLAB File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/69436-pawn-global-sensitivity-analysis-algorithm). (It is also available on my Github at <https://www.github.com/sriki18/pawn>).

The first example discussed in [^1] is the sensitivity of the Ishigami-Homma function. I have included the code for this in `ishigami_homma.m` and also included the code to reproduce Fig. 4 from [^1]. Below is the figure I reproduced (the original is [here](https://www.sciencedirect.com/science/article/pii/S1364815215000237#fig4)):

![Check out the repository!](/assets/PAWN/fig4.png)

## Giving credit

If you found this useful, please cite as :

> Srikiran Chandrasekaran (2018). PAWN Global Sensitivity Analysis algorithm (https://www.github.com/sriki18/pawn), GitHub.

## Additional information

The original authors of the PAWN paper maintain a website which provides [code for PAWN](https://www.safetoolbox.info/pawn-method/) and additionally a [cool sensitivity analysis toolbox](https://www.safetoolbox.info/info-and-documentation/) for MATLAB called `SAFE Toolbox`.

## References

[^1]: Pianosi, F., Wagener, T., 2015. A simple and efficient method for global sensitivity analysis based on cumulative distribution functions. Environ. Model. Softw. 67, 1–11. <https://doi.org/10.1016/j.envsoft.2015.01.004>