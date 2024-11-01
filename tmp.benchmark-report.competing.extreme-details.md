| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 372.2 ± 3.0 | 368.0 | 376.6 | 1.75 ± 0.02 |
| `dutree tmp.sample` | 4077.3 ± 9.9 | 4068.1 | 4102.7 | 19.22 ± 0.08 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 219.2 ± 1.3 | 217.0 | 222.1 | 1.03 ± 0.01 |
| `du --count-links --apparent-size tmp.sample` | 212.2 ± 0.8 | 210.7 | 213.4 | 1.00 |
