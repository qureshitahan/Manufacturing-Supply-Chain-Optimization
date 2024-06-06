# Supply Chain Optimization with Python: Streamlining Your Operations

## Description:
Welcome to the supply chain optimization journey! This repository is your guide to leveraging Python for smarter supply chain management. Let's dive into how we tackled the challenge of optimizing manufacturing facility locations, considering costs, demand, and logistics.

## Problem Statement:
As the head of supply chain management for an international manufacturing company, your task is to revamp the supply chain network for the next five years. With shipping costs on the rise and fluctuating demand forecasts, the goal is to make informed decisions to maintain lean and profitable operations.

## Excel Files Available:
To aid in our analysis, we have the following Excel files available:

- **variable_costs.xlsx:** Contains variable production costs for manufacturing facilities in different countries.
- **freight_costs.xlsx:** Displays shipping costs between different countries.
- **fixed_cost.xlsx:** Provides fixed production costs for manufacturing facilities in different countries.
- **capacity.xlsx:** Shows the capacity of manufacturing plants in different countries.
- **demand.xlsx:** Presents the demand for products in different countries.

## Approach:
We employed linear programming, a powerful problem-solving technique, to address the complexities of supply chain optimization. Armed with Python and libraries like Pandas and PuLP, we formulated a model to determine the most cost-effective setup for our manufacturing plants. By manipulating decision variables, setting constraints, and refining our objective function, we aimed to minimize costs while meeting customer demand.

## Results:
Here's what our analysis revealed:

### Plant Placement:
- Opt for high-capacity plants in the USA, Japan, and India.
- Establish a low-capacity plant in Brazil.
- No new plants needed in Germany.

### Production Plans:
- Produce as per the model's recommendations at each location.
- Maintain efficient logistics for smooth product movement between countries.

### Cost Analysis:
- Conduct a detailed breakdown of costs to identify areas of savings.
- Compare results with existing setups or alternative options for validation.

### What-If Scenarios:
- Explore different scenarios by adjusting demand forecasts or cost structures to gauge model sensitivity.

### Implementation Steps:
- Develop a plan for execution:
  - Establish manufacturing facilities based on the model's suggestions.
  - Onboard necessary personnel and organize logistics for seamless operations.
