# Curriculum-Guided Reinforcement Learning (C-GRL) for Imbalanced Classification

This repository contains Jupyter notebook implementations of **Curriculum-Guided Reinforcement Learning (C-GRL)** — a deep RL framework designed to handle **extreme class imbalance** in classification tasks. The model is benchmarked on two real-world medical datasets: **Stroke Prediction** and **Vitamin A Deficiency (VitA)**.

## 📂 Notebooks

| Notebook                              | Description                                      |
|---------------------------------------|--------------------------------------------------|
| `LoadingStroke.ipynb`                 | Loads and preprocesses the Stroke dataset        |
| `LoadingVitA.ipynb`                   | Loads and preprocesses the VitA dataset          |
| `Dueling DDQN Stroke-2024.ipynb`      | Dueling DDQN training on the Stroke dataset      |
| `Dueling DDQN Vitamin A.ipynb`        | Dueling DDQN training on the VitA dataset        |
| `C-GRL Implementation.ipynb`          | Full C-GRL training with curriculum and PER      |

## 🧠 Key Features

- **Curriculum Learning**: Trains progressively from balanced to imbalanced settings.
- **Prioritized Experience Replay (PER)**: Focuses on high-TD-error samples.
- **Dynamic Reward Scaling**: Adjusts class-wise reward magnitude based on imbalance ratio.
- **Dueling Double DQN Backbone**: Separates state value and action advantage.

## 📊 Datasets

- **Stroke Dataset**: Predictive classification of stroke risk based on clinical variables.
- **Vitamin A Deficiency Dataset**: Binary classification of VAD using symptom data from schoolchildren in Niger.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/C-GRL-Imbalanced-Classification.git
cd C-GRL-Imbalanced-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebooks:

```bash
jupyter notebook
```

## 📁 Repository Layout (Simplified)

```
notebooks/
│
├── LoadingStroke.ipynb
├── LoadingVitA.ipynb
├── Dueling DDQN Stroke-2024.ipynb
├── Dueling DDQN Vitamin A.ipynb
└── C-GRL Implementation.ipynb
```

## 📝 Citation

If you use this code or build upon it, please cite the accompanying paper (citation to be added).

## 📜 License

MIT License
