# MPC Implementation of Privacy-Preserving Billing for Local Energy Market

This repository contains an implementation of zone-based privacy-preserving billing for the local energy market while considering energy volume deviations of market participants from their bids, as proposed in [this paper](https://doi.org/10.48550/arXiv.2307.08778). The implementation is based on multiparty computation and was tested for three computing parties. The `Billing.mpc` file provides a privacy-preserving billing mechanism that doesn't take participants' locations on the grid into account. In contrast, the `ZoneBasedBilling.mpc` file incorporates users' locations.


## Installation
```
Install the MP-SPDZ software https://github.com/data61/MP-SPDZ.
mv Player-Data MP-SPDZ
mv Source/* MP-SPDZ/Programs/Source
```
## Usage

Refer to the [MP-SPDZ Documentation](https://mp-spdz.readthedocs.io) for detailed instructions on how to run the programes using any of MPC protocols supported by MP-SPDZ software. 



