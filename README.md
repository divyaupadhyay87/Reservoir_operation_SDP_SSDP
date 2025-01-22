# Reservoir_operation_SDP_SSDP
Designing Resilient Multipurpose Reservoir Operation Policies in the Presence of Internal Climate Variability

This repository provides the data, codes, and methodologies used for designing resilient multipurpose reservoir operation policies, considering the impact of internal climate variability. The approach optimizes reservoir operations to balance flood control, irrigation, municipal and industrial water demand, and hydropower production.
Features

    Objective Function: Integrates multiple aspects such as flood control, irrigation, municipal and industrial water demands, and hydropower production.
    Data Provided: Precipitation, Streamflow, Temperature, Irrigation water demand, Crop Coefficient: Used for estimating irrigation water demand.

Code Details: Benefit Calculation: A dedicated Python script calculates benefits associated with different operation policies.
    Transition Probability for SSDP: A separate script handles the computation of transition probabilities for the Sampling Stochastic Dynamic Programming (SSDP).
    Optimal Policy Determination:Python code for SSDP and Stochastic Dynamic Programming (SDP) algorithms to derive optimal policies. It also includes the final performance matrix for evaluating policy effectiveness.

Reproducibility: All data required to reproduce the figures from the associated paper are included in the repository.
How to Use:1. Review the individual Python files to understand the methodology:
2. Benefit calculation
3. Transition probability for SSDP
4. Optimal policy scripts for SSDP and SDP
Use the provided data to generate the figures.
