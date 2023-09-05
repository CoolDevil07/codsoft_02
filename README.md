# codsoft_02

# Tic-Tac-Toe AI Player

This project implements an AI agent that plays the classic game of Tic-Tac-Toe against a human player. The AI player uses the Minimax algorithm with or without Alpha-Beta Pruning to make strategic moves and ensure it's unbeatable. This project provides a hands-on opportunity to understand game theory and basic search algorithms.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [AI Algorithms](#ai-algorithms)


## Introduction

Tic-Tac-Toe is a classic two-player game where players take turns marking a 3x3 grid with their symbols (usually "X" and "O") with the goal of getting three of their symbols in a row, column, or diagonal. This project focuses on implementing an AI opponent that can play this game strategically, ensuring that it cannot be beaten.

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- Python (3.6 or higher) installed on your system.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-ai.git
   ```

2. Change your working directory to the project folder:

   ```bash
   cd tic-tac-toe-ai
   ```

3. Run the game script:

   ```bash
   python tic_tac_toe.py
   ```

   The game will start, and you can play against the AI opponent.

## Usage

- The game begins with an empty 3x3 grid, and you can make your moves by specifying the row and column where you want to place your symbol.
- The AI opponent will make its moves using the Minimax algorithm to maximize its chances of winning and minimize the chances of losing.
- The game will continue until one player wins or it ends in a draw.
- After the game ends, you can choose to play again.

## AI Algorithms

The AI player in this project uses the Minimax algorithm with or without Alpha-Beta Pruning to make its decisions. Minimax is a decision-making algorithm used in two-player games to minimize the possible loss for a worst-case scenario. Alpha-Beta Pruning is an optimization technique that reduces the number of nodes evaluated in the Minimax algorithm.

