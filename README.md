# AI Final Project: Simulating Adverse Selection in Used Car Markets
## Project Overview
This project utilizes agent-based modeling (ABM) to simulate adverse selection in the used car market, commonly referred to as the "lemons" problem. The goal of the simulation is to explore how certification and reputation systems influence market dynamics, price distribution, and efficiency.

The code is written using Python and leverages the Mesa library for agent-based modeling, Statsmodels and SciPy for statistical analysis, and Matplotlib and Seaborn for visualization. The project helps to better understand how information asymmetry leads to market inefficiencies and how mitigation strategies, like reputation systems and car certification, can be implemented to improve market outcomes.

## Features
Agent-based modeling (ABM) simulates interactions between buyers, sellers, and certifiers in a used car market.
Reputation Systems models how seller reputation affects car prices and buyer decisions.
Certification Mechanism analyzes the impact of third-party certification on market prices and consumer confidence.
Data Visualization generates visual outputs of price distributions, reputation scores, and buyer satisfaction over time.
## Project Goals
Simulate a market affected by adverse selection.
Examine the impact of reputation and certification systems on market dynamics.
Assess how buyer behavior, risk aversion, and seller strategies influence the market.
## Code Requirements
Python 3.x
Mesa (for agent-based modeling)
Matplotlib (for visualizations)
Seaborn (for advanced visualizations)
Statsmodels & SciPy (for statistical analysis)
##Installation
To run this simulation, you need to install the required dependencies. Use the following commands to set up your environment:

```bash
pip install mesa matplotlib seaborn statsmodels scipy
```

## How to Run

1. Clone this repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Run the simulation script:
    ```bash
    python AI_final_project.ipynb
    ```

## Files in the Repository
AI_final_project.ipynb: The main Python notebook containing the simulation code and analyses.
Nihad_R_36592723.pdf: Documentation describing the project background, objectives, methodology, and results.

## Methodology
The simulation models a fixed number of buyers and sellers, with varying car qualities (high-quality "peaches" vs low-quality "lemons"). Sellers can apply for
certification or rely on reputation to command higher prices, while buyers consider factors such as price, reputation, and certification when making purchases. Key behaviors modeled include:

- Sellers can adjust prices based on market conditions and choose to apply for certification. Buyers make decisions based on budget, reputation scores, and certification status.
- Certifiers provide third-party quality assurance, helping reduce information asymmetry. The simulation collects key metrics such as price distribution, reputation scores, sales volume, and buyer satisfaction.

##Results

- Reputation systems help high-quality sellers (peaches) command higher prices.
- Certification unexpectedly lowers prices, suggesting that buyers either undervalue certification or incur costs that reduce net prices.
- Market satisfaction improves over time, indicating that reputation and certification systems help address adverse selection but do not completely eliminate it.

##Future Work
The project identifies areas for future improvement:

- Extend the simulation to run over longer periods to capture more long-term trends.
- Incorporate a broader range of buyer and seller behaviors to simulate more complex interactions.
- Explore the effects of different policy interventions, such as subsidizing certification or penalizing low-quality sales.
