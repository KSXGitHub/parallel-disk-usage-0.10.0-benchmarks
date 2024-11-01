| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 90.4 ± 0.7 | 89.2 | 92.2 | 1.00 |
| `dua --count-hard-links tmp.sample` | 138.7 ± 3.6 | 129.8 | 144.5 | 1.53 ± 0.04 |
| `ncdu -o /dev/null -0 tmp.sample` | 215.8 ± 1.7 | 212.7 | 219.1 | 2.39 ± 0.03 |
| `gdu --non-interactive --no-progress tmp.sample` | 145.8 ± 2.0 | 141.6 | 148.3 | 1.61 ± 0.02 |
| `du --count-links --summarize tmp.sample` | 208.4 ± 1.0 | 206.0 | 209.7 | 2.31 ± 0.02 |
