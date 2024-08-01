# Capacitated Vehicle Routing Problem (CVRP)

## Abstract
This project addresses the Capacitated Vehicle Routing Problem (CVRP), a critical challenge faced by delivery companies that must efficiently distribute goods to various customers using a fleet of vehicles. The goal is to minimize the total travel cost while ensuring that all customer demands are met without exceeding the vehicle capacities.

## Problem Statement
The CVRP involves designing optimal routes for a fleet of vehicles from a central warehouse to multiple customers. Each vehicle has a capacity limit, and the objective is to minimize the total distance or cost traveled while ensuring that each customer is visited exactly once and vehicle capacities are not exceeded.

## Mathematical Formulation
The problem is mathematically formulated with the following key components:

- ![Alt text](/mathematical formulation 1.png)
- ![Alt text](/mathematical formulation 2.png)


## Complexity and Solution Approach
CVRP is an NP-hard problem, implying that no known polynomial-time algorithms can solve large instances exactly. The solution space grows exponentially with the number of customers, making exact solutions infeasible for large-scale problems. 

### Approaches for Solving CVRP:
- **Exact Algorithms**: Suitable for small instances, but impractical for large-scale problems.
- **Heuristics and Metaheuristics**: Genetic Algorithms is used to find good approximate solutions within reasonable time frames, a notebook showing different approaches is added.



## Conclusion
The project presents a systematic approach to solving the CVRP, balancing the need for cost-effective routes with the constraints imposed by vehicle capacities. While exact solutions are impractical for large instances, the use of advanced heuristics and metaheuristics offers a viable pathway to near-optimal solutions.

## Documentation
For more detailed information, including the methodologies, algorithms used, and results, please refer to the accompanying documentation provided in this repository.
