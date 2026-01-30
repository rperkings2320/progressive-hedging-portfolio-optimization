# Progressive Hedging for Multi-Period Portfolio Optimization (with Transaction Costs)

This repository contains my project for **IFT6512 – Stochastic Programming** (Université de Montréal).
The goal is to solve a **multi-period portfolio optimization** problem under uncertainty with **transaction costs** using the **Progressive Hedging (PH)** algorithm.

## Project Overview
 - **Problem**: dynamic asset allocation over multiple periods under scenario-based uncertainty
 - **Key features**: transaction costs, portfolio constraints, scenario decomposition
 - **Method**: Progressive Hedging (scenario-wise subproblems + penalty/consensus updates)
 - **Outputs**: optimal allocations by period, performance/risk indicators, convergence diagnostics

## Model (High-Level)
Typical elements used in the formulation:
- decision variables: holdings/trades over time
- objective: maximize expected utility/return (or minimize risk measure) net of transaction costs
- constraints: budget, long-only or bounds, self-financing constraints, rebalancing rules
- uncertainty: scenarios for prices/returns

## Method: Progressive Hedging (PH)
- scenario decomposition into independent subproblems
- iterative consensus on non-anticipativity constraints
- penalty parameter tuning and convergence monitoring
- comparison with baseline strategies (e.g., equal-weight) when applicable

## Tools
- **Julia**, **Python**, **R**, **Excel (Pivot Tables/TCD)**, **LaTeX**
> (Exact scripts and environments can be added/updated as the codebase grows.)

## Repository Structure 
- `report/` : project report (PDF)
- `src/` : PH implementation / optimization code
- `data/` : input data 
- `results/` : figures, tables, exported outputs
  

## Report
- The project report is provided as a PDF:
  - `Projet_Final_IFT6512.pdf`

## How to Run (placeholder)
1. Install Julia (and/or Python/R as needed)
2. Install dependencies (specified in `Project.toml` / `requirements.txt`)
3. Run the main script:
   - `julia src/main.jl`
4. Results will be exported to `results/`

## Notes
- This repository is for academic and portfolio purposes.
- If you reuse parts of this work, please cite appropriately.

## Author
- Rocky Perkings Kouegang Mossi  
- GitHub: https://github.com/rperkings2320  
- LinkedIn: https://www.linkedin.com/in/perkings

