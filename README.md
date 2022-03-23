# Bayes project - Hearts: a mixture model for count data

This project is conducted as part of the Bayesian Statistics and Hierarchical Models course by [Mathieu RIBATET](http://mribatet.perso.math.cnrs.fr/teaching.html#BAYES).

## Usage

### R

The R version of this project is the notebook file [Hearts R.Rmd](./Hearts%20R.Rmd).


### Python

The Python version of this project is the notebook file [Python version/main.ipynb](Python%20version/main.ipynb).

## Results

After running the Python version with the parameters:
- N = 10000 (Length of the chain)
- Burnin = 1000 (Number of elements to drop at the beginning of the chain)
- Standard deviation for Metropolis-Hastings gaussian random walk
  - Alpha: 0.05
  - Delta: 1

We get the following results

|       |       alpha |        beta |       delta |       theta |
|-------|------------:|------------:|------------:|------------:|
| count | 9001.000000 | 9001.000000 | 9001.000000 | 9001.000000 |
| mean  |   -0.457498 |    0.654220 |    0.292613 |    0.566757 |
| std   |    0.258600 |    0.169784 |    0.623994 |    0.141027 |
| min   |   -1.369842 |    0.254147 |   -2.279330 |    0.092849 |
| 2.5%  |   -0.982563 |    0.374351 |   -0.882364 |    0.292688 |
| 50\%  |   -0.458911 |    0.631972 |    0.296920 |    0.573690 |
| 97.5% |    0.027647 |    1.028032 |    1.528998 |    0.821860 |
| max   |    0.292419 |    1.339665 |    2.437030 |    0.919608 |

## Authors

- Karim CHAKROUN
- Maxime GOURCEYRAUD
- Charles MIRANDA
- Vincent SEVESTRE