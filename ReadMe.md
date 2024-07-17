
# Blackjack Simulation

This repository contains a Jupyter notebook that simulates multiple rounds of the Blackjack card game. The simulation includes betting strategies and tracks the player's balance over time.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Notebook Contents](#notebook-contents)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Blackjack, also known as 21, is one of the most popular casino card games. This project simulates the game of Blackjack, implementing basic game rules, betting strategies, and balance tracking. The simulation runs multiple games to analyze the effectiveness of the betting strategy and visualizes the results.

## Features

- Simulation of multiple Blackjack games
- Basic betting strategy
- Balance tracking and visualization
- Histogram of final balances
- Calculation of mean balance

## Requirements

- Python 3.6 or higher
- Jupyter Notebook
- Matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blackjack-simulation.git
   cd blackjack-simulation
   ```

2. Install the required Python packages:

   ```bash
   pip install matplotlib numpy jupyter
   ```

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook blackjack.ipynb
   ```

4. Run the notebook cells to simulate the Blackjack games and visualize the results.

## Notebook Contents

The notebook includes the following sections:

1. **Imports and Setup**: Importing libraries and setting up the game environment.
2. **Deck and Game Logic**: Functions to create and manage the deck, deal cards, calculate points, and implement the game logic.
3. **Simulation Loop**: A loop to simulate multiple games, handle betting, check for wins/losses, and update balance.
4. **Results and Visualization**: Plotting histograms of the final balances and printing summary statistics like the mean balance.

## Results

The simulation outputs a histogram of the final balances after multiple games and prints the mean balance. This helps in understanding the effectiveness of the betting strategy implemented.

![Balance Histogram](ss_upcoming)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to suggest.

## Disclaimer
This project is for educational and entertainment purposes only. Gambling involves risk, and there are no guaranteed strategies for success.