| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 104.4 ± 0.3 | 103.9 | 105.1 | 1.00 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 217.6 ± 1.3 | 215.1 | 219.3 | 2.08 ± 0.01 |
| `gdu --non-interactive tmp.sample` | 144.6 ± 2.2 | 141.3 | 149.3 | 1.38 ± 0.02 |
