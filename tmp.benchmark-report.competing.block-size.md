| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=block-size tmp.sample` | 90.7 ± 0.6 | 89.6 | 92.7 | 1.00 |
| `dust tmp.sample` | 116.4 ± 0.8 | 114.8 | 117.8 | 1.28 ± 0.01 |
| `dua --count-hard-links tmp.sample` | 138.1 ± 3.7 | 130.6 | 144.3 | 1.52 ± 0.04 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 217.6 ± 1.3 | 216.1 | 219.6 | 2.40 ± 0.02 |
| `gdu --non-interactive --no-progress tmp.sample` | 146.0 ± 2.4 | 142.1 | 153.2 | 1.61 ± 0.03 |
| `du --count-links tmp.sample` | 211.7 ± 1.3 | 209.9 | 214.5 | 2.33 ± 0.02 |
