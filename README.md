# Sparse Importance Is Not a Sparse Decomposition: A Routing-Consistency Check for Parameter Decomposition

This repository holds the code for reproducing the results of the paper:

Knud Rasmus Sønderbek, Danial Namazifard, Lukas Galke Poech. Sparse Importance Is Not a Sparse Decomposition: A Routing-Consistency Check for Parameter Decomposition. EACL 2027 (Findings).

Our works builds on [stochastic parameter decomposition](https://arxiv.org/abs/2506.20790) and makes several key contributions are 

- a new toy model of geometry
- generalize SPD to rank-k subcomponents
- a routing-consistency check

The most relevant code changes can be found within `src/spd/models` and `src/spd/experiments`.

The rest of the code was minimally altered to make it compatible.

## Installation

Installation instructions are found within the `src` folder, in the official SPD README.

## Reproducing the results

The repository as published contains the relational variant (RSPD) and the routing-consistency check. The SPD and SPD + attention baselines were run with the sigmoid causal-importance function and the $p$-norm importance-minimality loss of Bushnaq et al. (2025).
