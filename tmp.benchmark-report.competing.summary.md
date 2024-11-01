| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 89.9 ± 0.6 | 89.1 | 91.4 | 1.00 |
| `dutree --summary tmp.sample` | 382.0 ± 1.5 | 379.7 | 384.7 | 4.25 ± 0.03 |
| `dua --count-hard-links tmp.sample` | 137.5 ± 4.6 | 127.0 | 144.6 | 1.53 ± 0.05 |
| `du --count-links --summarize tmp.sample` | 207.8 ± 1.2 | 206.5 | 210.8 | 2.31 ± 0.02 |
