# Interactive Statistics Visualizations

This folder contains interactive, browser-based lessons designed to build intuition for probability, statistics, machine learning, and artificial intelligence. Each lesson uses simulation and responsive graphics to connect mathematical ideas with observable behavior. The collection is intended to grow as new concepts and tools are added.

## Documents

- **`Fitting_Distributions_to_Data.html`** — Explores fitting normal, exponential, and gamma models to simulated data. Users can change the sample size and source distribution, tune model parameters, compare a fitted density with the sample histogram, and observe how the log-likelihood changes.

- **`MLE_Poisson_data_sensitivity.html`** — Develops the Poisson maximum likelihood estimator from asbestos-fiber counts observed in 23 grid squares. Users can edit the data table and see the maximum likelihood estimate, observed-count histogram, fitted probability mass function, likelihood, and log-likelihood update together in real time.

- **`Estimator_Sampling_Distribution_Uniform.html`** — Introduces sampling distributions through estimation of the endpoint θ in a Uniform(0, θ) population. A guided simulation compares `2X̄` and the sample maximum across repeated samples, then relates their empirical histograms to theoretical density, bias, and variance.

- **`Confidence_Interval_Normal.html`** — Demonstrates repeated-sample confidence intervals for the mean of a Normal population. It constructs the interval `X̄ ± 1.96 S/√n` for 100 samples, displays the intervals beside the changing sample histogram, and tallies how often they contain the true mean.

- **`Mean_Sampling_Distribution_Large_Sample.html`** — Builds sampling distributions of the mean for `n = 1, 10, 100`. Learners generate the first three repetitions manually, then watch 197 more accumulate in real time while current-sample histograms, recorded means, Normal approximations, and convergence diagnostics update.

- **`README.md`** — Describes the purpose of the project and provides this catalog of its documents.

## Using the lessons

Open any `.html` file in a modern web browser. The lessons are self-contained and require no installation or internet connection.
