# Statistics and Probability Calculator

A self-contained, single-file web application covering scientific computation, descriptive statistics, probability distributions, and Bayesian analysis. No dependencies, no build step — open `index.html` in any modern browser.

## Features

### Scientific Calculator
Full expression calculator with trig (sin, cos, tan and inverses), hyperbolic functions, log/ln, roots, powers, factorial, absolute value, π and e constants, percentage, and memory registers (MC/MR/M+/M−). Supports DEG/RAD toggle and keyboard input.

### Descriptive Statistics
Paste any comma-, space-, or newline-separated dataset and compute: count, sum, mean, median, mode, min/max/range, quartiles (Q1/Q3/IQR), population and sample variance, population and sample standard deviation, standard error of the mean, coefficient of variation, skewness, and excess kurtosis.

### Probability Distributions
- **Combinations & Permutations** — C(n, r) and P(n, r)
- **Binomial** — PMF, CDF, complementary CDF, mean, variance, std dev
- **Normal** — PDF, CDF, z-score, area between two values
- **Poisson** — PMF, CDF, mean, std dev
- **Geometric** — PMF, CDF, mean, variance, std dev

### Bayesian Analysis
- **Bayes' Theorem** — prior, likelihood, posterior with odds and likelihood ratio
- **Beta-Binomial Update** — conjugate prior updating with 95% credible interval
- **Bayes Factor** — hypothesis testing with Jeffreys' scale interpretation

### Analytics Panel
A sticky side panel shows live session tracking (duration, calculation count, tab activity, top functions used) alongside simulated site traffic (active users, daily views, hourly sparkline, weekly chart, top regions, device breakdown).

## Getting Started

No installation required.

```bash
git clone https://github.com/kevb2029-maker/003-Scientific-Calculator-Probability-Statistics.git
cd 003-Scientific-Calculator-Probability-Statistics
open index.html        # macOS
# or
start index.html       # Windows
# or just drag index.html into any browser
```

## Usage

Each calculator mode lives in its own tab. Inputs validate on submission and display results immediately. The scientific calculator also responds to keyboard input when the Scientific tab is active.

To report a bug or request a feature, use the contact form at the bottom of the page.

## Tech Stack

- Pure HTML, CSS, and JavaScript
- No frameworks, no dependencies, no build tooling
- Single file — `index.html`

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT — see [LICENSE](LICENSE).
