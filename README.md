# Transfer Entropy Analysis

Implementation of Transfer Entropy (TE) for analyzing directional information flow between variables.

## Overview
This code demonstrates the calculation of transfer entropy and related information theory measures to analyze directional relationships between time series variables.

## Key Concepts
- **Entropy**: Average uncertainty of a random variable
- **Mutual Information**: Shared information between two variables
- **Transfer Entropy**: Conditional mutual information with time delay

## Mathematical Framework
Core equations implemented:
- Shannon Entropy: H(X) = -∑p(x)log p(x)
- Transfer Entropy: TE = H(Xfuture|Xpast) - H(Xfuture|Xpast,Ypast)

## Example Implementation
Includes:
1. Setup of required Python packages
2. Implementation of TE calculation functions using dit package
3. Simulation examples demonstrating time-delayed mutual information and transfer entropy

## References
This repo is related to the post: ["Transfer Entropy"](http://pablomflores.com/transfer-entropy) by Pablo M. Flores.

## License
This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
