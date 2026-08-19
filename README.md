# 🤖 CS50's Introduction to Artificial Intelligence with Python

My solutions and project implementations for **Harvard University's CS50 AI (CS50's Introduction to Artificial Intelligence with Python)**.

> [!NOTE]
> **Academic Honesty Notice**: This repository is shared for educational portfolio demonstration. Please adhere to [CS50 Academic Honesty Policy](https://cs50.harvard.edu/ai/syllabus/#academic-honesty) if currently enrolled in the course.

---

## 📚 Curriculum & Project Implementations

| Week | Topic | Project | Description & Core Algorithms |
| :--- | :--- | :--- | :--- |
| **0. Search** | Graph Search & Adversarial Search | [Degrees](week0/degrees) | Shortest connection path between actors using **Breadth-First Search (BFS)** |
| | | [Tic-Tac-Toe](week0/tictactoe) | Unbeatable AI player implemented using the **Minimax Algorithm** with Alpha-Beta Pruning |
| **1. Knowledge** | Propositional Logic & Inference | [Knights](week1/knights) | Logical deduction puzzle solver using **Propositional Knowledge Bases & Model Checking** |
| | | [Minesweeper](week1/minesweeper) | Automated Minesweeper AI agent drawing deterministic logical inferences from known counts |
| **2. Uncertainty** | Probability & Bayesian Models | [PageRank](week2/pagerank) | Webpage importance ranking using **Random Surfer Model (Markov Chains)** & **Iterative Formula** |
| | | [Heredity](week2/heredity) | Genetic trait likelihood estimation using **Bayesian Networks & Joint Probability Distributions** |
| **3. Optimization** | Constraint Satisfaction Problems | [Crossword](week3/crossword) | Crossword puzzle generator using **AC-3 Constraint Propagation** & **Backtracking Search** |
| **4. Learning** | Supervised Machine Learning | [Shopping](week4/shopping) | Predicts customer purchasing intent using **K-Nearest Neighbors (k-NN)** with sensitivity/specificity metrics |
| | | [Nim](week4/nim) | Self-play game engine trained to master Nim via **Q-Learning (Reinforcement Learning)** |
| **5. Neural Networks** | Deep Learning & Computer Vision | [Traffic](week5/traffic) | Real-time road sign classification using **Convolutional Neural Networks (CNNs)** in TensorFlow |
| **6. Language** | Natural Language Processing | [Parser](week6/parser) | Sentence structure analysis and noun phrase chunking using **Context-Free Grammars (NLTK)** |
| | | [Questions](week6/questions) | Question-answering search engine using **TF-IDF Term Frequency & Document Retrieval** |

---

## 🛠️ Installation & Environment Setup

```bash
git clone https://github.com/Saiyam008/cs50ai.git
cd cs50ai

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install core dependencies
pip install pygame scikit-learn tensorflow nltk numpy
```

---

## 📄 License

This repository is maintained for educational demonstration purposes.
