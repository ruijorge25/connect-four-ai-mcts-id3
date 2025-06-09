# connect-four-ai-mcts-id3
Connect Four AI using Monte Carlo Tree Search (MCTS) and ID3 decision tree, with gameplay interface and dataset generation.

# 🎮 Connect Four AI — MCTS & ID3

This project implements an AI system for playing Connect Four using **Monte Carlo Tree Search (MCTS)** and a **Decision Tree (ID3)** model trained from simulated games.

## 🧠 Main Features

- ✅ Playable Connect Four game with `pygame`
- 🧠 AI opponent using MCTS with three difficulty levels
- 📊 Game state dataset generation from MCTS simulations
- 🌳 Implementation of ID3 decision tree (from scratch)
- 🧪 Evaluation with confusion matrices and accuracy metrics
- ⚙️ Logistic regression model with imbalance penalty for comparison

## 📁 Project Structure

- `button.py` – Helper class for interactive buttons in the menu (pygame)
- `assets/` – Images and fonts for the graphical interface
- `NotebookGrupo4TP1.ipynb` – Main notebook with MCTS, dataset creation, ID3 training, and model evaluation
- `dataset_connect4.csv` – Dataset generated from MCTS gameplay
- `iris.csv` – Auxiliary dataset for model comparison (e.g., logistic regression)

## 🧪 Technologies Used

- Python (Jupyter Notebook)
- `pygame`
- `pandas`, `numpy`
- Custom implementation of ID3
- Evaluation via `scikit-learn` (confusion matrix, accuracy, etc.)

## 📌 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/connect-four-ai-mcts-id3.git
   cd connect-four-ai-mcts-id3
