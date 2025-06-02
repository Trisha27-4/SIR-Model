# SIR-Model
Built a custom SIR model and applied it to a synthetic Gaussian graph and a real-world internet topology graph. Evaluated how network structure, recurrence, and isolation frequency affected epidemic spread, peak infection rates, and basic reproduction numbers.

# Highlights:

- Simulated SIR model across two graph types
- Compared infection curves with and without isolation
- Introduced recurrent infection modeling with varying isolation intervals
- Visualized infected/susceptible/recovered curves over time

Tech Stack: Python, NetworkX, Pandas, Matplotlib
# 🧬 Epidemic Simulation on Graphs (SIR Model)

Simulates the spread of infectious diseases using the SIR model on different types of networks, including a synthetic Gaussian graph and a real-world internet topology dataset.

## 🧠 Objectives
- Adapt the SIR model to graph-based simulation
- Study epidemic spread dynamics on sparse vs. dense graphs
- Evaluate isolation strategies and recurrent infections
- Visualize peak infection timing, R₀, and total attack rate

## 📊 Graph Types
- Random Gaussian Graph
- Real-World Topology (AS-level network)

## 📈 Key Features
- Customizable infection, recovery, and recurrence rates
- Adjustable isolation intervals
- Time-series plots for S, I, R compartments
- Comparative analysis across multiple network types

## 🛠 Tools & Technologies
Python · NetworkX · Pandas · Matplotlib

## 📁 Structure
- `sir_simulation.ipynb`: Core simulations and analysis
- `graphs/`: Network files (e.g., GML)
- `plots/`: Output figures for different simulation runs

## 📚 References
- Newman M.E.J. (2002) Spread of epidemic disease on networks
- Network datasets: [UMich Netdata](https://public.websites.umich.edu/~mejn/netdata/)
