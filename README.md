# QOSF Cohort 9 Screening Tasks

Repository for Submission of QOSF Screening Tasks - Cohort 9

I have attempted Task 4 MIS using QAOA from the list of Screening Tasks for Cohort 9.

## Notebook Guide

1. *QAOA_gate_pennylane.ipynb* has the gate based implementation of QAOA using ***Pennylane***. Majority of the theory of QAOA and implementation is given in this notebook.  

2. *QAOA_analog_pulser.ipynb* has the analog based implementation of QAOA using ***Pulser***.

3. *Result Comparison.md* includes some comments about the comparison between the obtained results.

## Libraries

### Graph Creation

* [***Networkx***](https://networkx.org/)

### QUBO formulation

* [***docplex***](https://pypi.org/project/docplex/) 

### Quantum Computing Model

* [***Pennylane***](https://pennylane.ai/) for gate based QAOA
* [***Pulser***](https://github.com/pasqal-io/Pulser) for analog based QAOA

> All the required packages are listed in the ***requirements**.txt* file.<p>
> **Python** - 3.10.14
