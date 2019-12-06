# Determine an efficient tuning order for multiple dependent database futures

This repository contains AMPL implementations of the integer linear program specified in the paper Self-Driving Database Systems: A Conceptual Approach. In their current state, the programs need AMPL and the Gurobi solver. After starting AMPL, run the programs with `include PROGRAM_NAME.txt`


## Program 1 - tuning_order_index_compression_clustering

This program contains code that determines an efficient tuning order for index selection, compression selection and clustering. Workload costs are determined experimentally for the main memory research database [Hyrise](https://github.com/hyrise/hyrise).

## Program 2 - tuning_order_scalability_example

The second program contains the code to generate data for the scalability examples (Example 1), and thereby the results for Table 3, 4, and 5.
