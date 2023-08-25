# MPC Implementation of Privacy-Preserving Billing for Local Energy Market

This repository contains an implementation of zone-based privacy-preserving billing for the local energy market while considering energy volume deviations of market participants from their bids. The implementation is based on multiparty computation and was tested for three computing parties, as proposed in [this paper](https://doi.org/10.48550/arXiv.2307.08778). The `Billing.mpc` file provides a privacy-preserving billing mechanism that doesn't take participants' locations on the grid into account. In contrast, the `ZoneBasedBilling.mpc` file incorporates users' locations.

## Instructions

Follow these steps to set up and run the implementation:

1. Download the [Multi-Protocol SPDZ](https://github.com/data61/MP-SPDZ/releases) package and extract its contents.

2. Copy the `Billing.mpc` and `ZoneBasedBilling.mpc` files from this repository to the `Programs/Source` directory within the extracted MP-SPDZ folder.

3. Refer to the [MP-SPDZ Documentation](https://mp-spdz.readthedocs.io) for detailed instructions on how to run the MPC protocols using the MP-SPDZ software. Choose any of the protocols supported by the MP-SPDZ software to execute `Billing.mpc` and `ZoneBasedBilling.mpc`. 

Feel free to reach out if you encounter any issues or need further assistance.

