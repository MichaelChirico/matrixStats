# CRAN submission matrixStats 1.4.1

on 2024-09-06

This submission addresses a UBSan error introduced in 1.4.0.


## Notes not sent to CRAN

### R CMD check validation

The package has been verified using `R CMD check --as-cran` on:

| R version | GitHub | mac/win-builder |
| --------- | ------ | --------------- |
| 4.0.x     | L      |                 |
| 4.1.x     | L      |                 |
| 4.2.x     | L      |                 |
| 4.3.x     | L   W  |                 |
| 4.4.x     | L M W  | M1              |
| devel     | L   W  |    W            |

*Legend: OS: L = Linux, M = macOS, M1 = macOS M1, W = Windows*
