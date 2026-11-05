
## Minjee Kim
Ph.D. candidate in Statistics, Texas A&M University. Expected May 2027.

I work on statistical identifiability, Bayesian inference, and uncertainty quantification, including how to assess whether computational estimates are reliable when observations are partial, noisy, or lagged.

Coauthor, [Prevalence study in Cameroon identifies Brucella abortus as the endemic Brucella species in livestock](https://www.nature.com/articles/s41467-025-66515-z), *Nature Communications* (2025).

### Areas of interest
* Bayesian latent-variable models
* Uncertainty quantification
* Partial and noisy observations
* Model diagnostics & validation
* Monte Carlo methods & computational inference

 

### Featured research project

**[Bayesian Latent-Severity Modeling for Diagnostic Test Evaluation](https://github.com/minjee-kim/Bayesian-latent-severity-LCA)**

Developed a Bayesian latent-class model for estimating disease prevalence and diagnostic-test accuracy when no gold standard is available. The model introduces a **continuous subject-level disease-severity factor** in a probit formulation, allowing dependence among imperfect diagnostic tests without introducing a separate random effect for every test and class. Investigated identifiability and prior specification, implemented posterior inference using data augmentation and MCMC, and evaluated the approach through simulation-based parameter recovery and a reanalysis of published Strongyloides stool/serology data. Compared the severity formulation with conditional-independence and random-effects alternatives.

<p align="center">
  <a href="https://github.com/minjee-kim/Bayesian-latent-severity-LCA">
    <img src="https://raw.githubusercontent.com/minjee-kim/Bayesian-latent-severity-LCA/main/figures/Vij_plot.png" alt="Bayesian latent severity model: latent score distributions for diagnostic tests" width="510">
  </a>
</p>

[Methodology, code, and simulation study](https://github.com/minjee-kim/Bayesian-latent-severity-LCA)

---

**[FLOCK — Monte Carlo Exploration & Algorithm Benchmarking](https://github.com/minjee-kim/FLOCK)**

Designed and evaluated coordinated exploration strategies for challenging posterior distributions, including covariance-guided proposals, repulsive chains, and importance-sampling consolidation. Benchmarked estimation accuracy against MCMC baselines under controlled computational budgets, identifying promising results in selected simulations and limitations in posterior inference.

<p align="center">
  <a href="https://github.com/minjee-kim/FLOCK">
    <img src="https://raw.githubusercontent.com/minjee-kim/FLOCK/main/figures/geometric_search.svg" alt="FLOCK geometry-guided posterior exploration" width="510">
  </a>
</p>

[Research report (PDF)](https://github.com/minjee-kim/FLOCK/blob/main/paper/main.pdf) · [Source code and experiments](https://github.com/minjee-kim/FLOCK)

*Exploratory methodological research; not a validated or peer-reviewed MCMC algorithm.*

### Projects

* **Applied analysis.** [NYC rolling sales price recovery](https://github.com/minjee-kim/NYC-appraisal): latent price recovery from lagged assessments, using a Bayesian state-space desmoothing filter for New York class 1 property.
* **Applied analysis.** [A/B testing and experimental design](https://github.com/minjee-kim/ab-testing): metric definition, design checks, and treatment-effect estimates for Cookie Cats, the Udacity free-trial screener, and the Upworthy archive.
* **R package development.** [nhanesGraph](https://github.com/minjee-kim/nhanesGraph): search and download of public-use continuous NHANES files from the current CDC links, 1999–2000 through August 2021–August 2023.
