| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 90.3 ± 0.8 | 89.2 | 92.3 | 1.00 |
| `du --count-links tmp.sample` | 210.1 ± 1.8 | 207.6 | 213.6 | 2.33 ± 0.03 |
| `dua --count-hard-links tmp.sample` | 138.0 ± 3.7 | 130.9 | 144.5 | 1.53 ± 0.04 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 216.3 ± 2.0 | 213.8 | 221.0 | 2.40 ± 0.03 |
| `gdu --non-interactive --no-progress tmp.sample` | 145.4 ± 1.6 | 142.5 | 148.2 | 1.61 ± 0.02 |
