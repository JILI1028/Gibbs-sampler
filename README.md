# Gibbs-sampler
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    <li>
      <a href="#getting-started">Getting Started</a>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is to give a simple explanation of how and why the Gibbs sampler works and reproduce the simulations in Casella and George (1992). The Gibbs sampler is a technique for generating random variables from a marginal distribution indirectly, without having to calculate the density. We can illustrate the application of the Gibbs sampler in bivariate situations and some higher dimensional cases. However, the Gibbs sampler doesn't always
converge. The report will contain 3 examples and 5 figures to show the histograms of samples from Gibbs sampling and make some comparisons with the true marginal densities.

By using the Gibbs sampler, we are able to avoid difficult calculations, replacing them with a sequence of easier calculations. Gelfand and Smith (1990) state that it also has potential in a wide variety of conventional statistical problems.

<!-- GETTING STARTED -->
## Getting Started

* Example1: Beta-Binomial distribution

This example is to compare two histograms of samples from the Beta-Binomial distribution. One was obtained using Gibbs sampling, and the other was generated directly from the true marginal.

<div align="center">
<img src="https://github.com/JILI1028/Gibbs-sampler/blob/main/images/nas_mwphunnamed-chunk-2-1.png" width="500" height="400">
</div>

* Example 2: Exponential distributions

This example uses equation(2) in the report to estimate marginal distribution. X and Y both have conditional distributions that are exponential distributions. The form of this marginal is not easily calculable, so the Gibbs sampler can be applied to the conditionals to obtain the characteristic of f(x).

<div align="center">
<img src="https://github.com/JILI1028/Gibbs-sampler/blob/main/images/nas_mwphunnamed-chunk-3-1.png" width="500" height="400">
</div>

* Example1 (continued)

Analogous to equation (2), we can also estimate the marginal probabilities of X in Example 1.

<div align="center">
<img src="https://github.com/JILI1028/Gibbs-sampler/blob/main/images/nas_mwphunnamed-chunk-4-1.png" width="500" height="400">
</div>

* Example 2 (continued)

This example shows that proper conditional distributions will not always determine a proper marginal distribution. In this case, when the Gibbs sampler is applied to the conditional densities, convergence breaks down.

<div align="center">
<img src="https://github.com/JILI1028/Gibbs-sampler/blob/main/images/nas_mwphunnamed-chunk-5-1.png" width="500" height="400">
</div>

* Example3: More Than Two Variables

Example 3 is to calculate the marginal distribution in a problem with more than two random variables X, Y, and Z. The iteration will also solve the fixed-point equation like example 2 (continued).

<div align="center">
<img src="https://github.com/JILI1028/Gibbs-sampler/blob/main/images/nas_mwphunnamed-chunk-6-1.png" width="500" height="400">
</div>

<!-- CONTACT -->
## Contact

Ji Li- jil1@umbc.edu

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->

<!-- MARKDOWN LINKS & IMAGES -->
