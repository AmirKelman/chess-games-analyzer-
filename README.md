# Chess Games Analyzer
A data science project analyzing 30,000 chess games from Lichess.org using network analysis, machine learning, and statistical modeling to extract insights about player behavior and game dynamics.
## Key Findings

- Community Detection: Identified distinct player communities using Louvain algorithm - surprisingly, players don't prefer opponents with similar ratings
- Influence Ranking: Built PageRank-based system identifying most influential players (correlation: 0.61, p-value: 1.7e-30)
- Game Volatility: Challenged assumptions about skill vs. chaos - no significant correlation between Elo rating and game volatility

## Technical Implementation
Data Processing: 30K games (60MB) in PGN format from January 2017

- Network analysis with weighted graphs (player interactions)
- Stockfish chess engine for position evaluation
- K-means clustering and statistical validation

**Technologies**: Python, NetworkX, Scikit-learn, Pandas, Stockfish Engine
## Methodologies

-  Community Analysis: Louvain algorithm on player interaction graphs
- Influence Modeling: PageRank with custom edge weights (games played, outcomes, game quality)
- Volatility Metrics: Position evaluation swings + mistake frequency analysis

## Results

- Successfully identified player communities with modularity-based validation
- Ranked top influential players with strong statistical significance
- Developed novel "chaos score" metric for game analysis
- Created comprehensive visualizations and similarity matrices

## Impact
This project demonstrates proficiency in:

- Large-scale data analysis and preprocessing
- Graph theory and network analysis algorithms
- Machine learning clustering and validation techniques
- Statistical modeling and hypothesis testing
- Data visualization and insight communication

---
**Demo**: [YouTube Video](https://youtu.be/UEmQcQigfwo) | **Full Report**: Available in repository

University of Jerusalem Final Project - Introduction to Data Science
