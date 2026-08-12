# Electric Appliance Store Inventory Simulation

## Project Overview

An academic simulation project developed for the **Systems Modeling and Simulation** course at Cairo University.

The project implements **Problem II – Electric Appliance Store**, which models inventory management for two products under stochastic demand and lead-time conditions.

## Problem Description

The simulated store sells two products, A and B, using a two-level inventory system:

- A showroom with a total capacity of 10 units.
- A main inventory with a total capacity of 30 units.
- Stochastic daily demand for both products.
- Automatic replenishment from the inventory to the showroom.
- Periodic inventory review.
- Stochastic lead times for incoming orders.
- Shortage and lost-sales tracking.

## Simulation Parameters

- Review period (N): 4 days
- Order quantity for Product A (mA): 6 units
- Order quantity for Product B (mB): 6 units
- Initial showroom stock: 5 units of A and 5 units of B
- Initial inventory stock: 15 units of A and 15 units of B
- Showroom capacity: 10 units
- Inventory capacity: 30 units

## Simulation Analysis

The simulation evaluates:

- Average ending units in the showroom.
- Average ending units in the inventory.
- Number of days with shortage conditions.
- Theoretical versus experimental average demand for Products A and B.
- Theoretical versus experimental average lead time.
- Discussion of the effect of different review-period values on inventory shortages.
- Discussion of the effect of different order quantities on inventory shortages.
- The trade-off between reducing shortages and increasing inventory-related costs.

The effects of alternative values for the review period and order quantities were discussed as part of the analysis. However, determining the optimal values for these parameters would require further investigation.

## Results

The simulation was tested over different simulation horizons to evaluate system behavior and the reliability of the generated stochastic variables.

For the 10,000-day simulation:

- Product A shortage occurred on 5,656 days (56.6%).
- Product B shortage occurred on 3,549 days (35.5%).
- The theoretical average demand for Product A was 2.80 units/day.
- The theoretical average demand for Product B was 2.10 units/day.
- The experimental demand averages were close to their theoretical values.
- The theoretical average lead time was 1.85 days, with the experimental results showing close agreement.

The results demonstrate that the simulation provides a representation of the inventory system and allows the effect of demand, lead time, review periods, and order quantities on inventory performance to be analyzed.

## Data Visualization

The project uses graphical analysis to visualize:

- Showroom inventory distributions.
- Main inventory distributions.
- Inventory and demand behavior.
- Simulation results and shortage conditions.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib

## Files

- `Electric Appliance Store.py` — Python implementation of the inventory simulation.
- `Electric Appliance Store.docx` — Project report containing the simulation analysis, results, graphs, and conclusions.
- `DS331 Project - 2025 Term Project.pdf` — Original course project statement and requirements.

## Course Information

**Course:** Systems Modeling and Simulation  
**Course Code:** DS331  
**Department:** Operations Research and Decision Support  
**Faculty:** Computers and Artificial Intelligence  
**Cairo University**  
**Term Project — 2025**
