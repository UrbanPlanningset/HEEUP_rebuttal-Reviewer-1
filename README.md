Q2 Supplemental

HEEUP vs [1] in difference.

| Difference   | HEEUP                                        | [1]                                      | Remarks                                     |
|--------------|----------------------------------------------|-----------------------------------------------|---------------------------------------------|
| Objective    | Minimize energy consumption for efficient urban layout | Adapt to complex terrain, optimize urban community spatial planning | Focus on energy efficiency vs. terrain adaptability |
| Strategy     | Hierarchical decision-making: from macro to micro optimization | Sequential decision-making: dynamic adaptation, continuous planning | Hierarchical vs. sequential decision-making process |
| State        | Comprehensive urban feature encoding (GAT+GAE), capturing full-spectrum multi-dimensional information | Progress and data encoding (GNN+Encoder), reflecting real-time planning dynamics | GAT enhances feature interrelation vs. GNN focuses on progress and statistics |
| Action       | Multi-dimensional actions, adjusting various aspects of urban planning from macro to micro | Focused on single decision-making for land use and roads | Multi-level refinement vs. single-point decision-making |
| Reward       | Energy efficiency as the core metric at each hierarchical level | Service quality, ecological balance, and traffic flow efficiency make up a composite reward system | Tiered focus on energy vs. diverse urban benefits |

HEEUP vs [1] in result.

| City   | MIAMI HEEUP | MIAMI [1] | Alq HEEUP | Alq [1] |
|--------|-------------|----------------|-----------|--------------|
| Exp. 1 | 9.05%       | -1.17%         | 7.30%     | -0.32%       |
| Exp. 2 | 7.72%       | 1.66%          | 7.25%     | -0.96%       |
| Exp. 3 | 8.74%       | 1.24%          | 7.15%     | 1.21%        |
| Exp. 4 | 8.86%       | 1.55%          | 7.33%     | 1.15%        |
| Exp. 5 | 9.11%       | 1.41%          | 7.19%     | 0.75%        |
| **Average** | **8.70%**   | **0.94%**      | **7.24%** | **0.37%**    |

**Table: HEEUP is based on the principle of energy saving, and [1] is based on the principle of service request.**
