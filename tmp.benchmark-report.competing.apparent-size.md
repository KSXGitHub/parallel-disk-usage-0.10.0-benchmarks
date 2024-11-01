| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=apparent-size tmp.sample` | 92.0 ± 1.6 | 90.4 | 97.9 | 1.00 |
| `dust --apparent-size tmp.sample` | 116.4 ± 13.6 | 105.2 | 152.8 | 1.27 ± 0.15 |
| `dua --count-hard-links --apparent-size tmp.sample` | 143.3 ± 12.4 | 125.2 | 164.7 | 1.56 ± 0.14 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 218.7 ± 1.7 | 216.8 | 221.6 | 2.38 ± 0.04 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 145.8 ± 3.3 | 141.9 | 155.2 | 1.59 ± 0.04 |
| `du --count-links --apparent-size tmp.sample` | 210.8 ± 0.9 | 209.7 | 212.2 | 2.29 ± 0.04 |
