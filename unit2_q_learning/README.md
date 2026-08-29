# Unit 2: Introduction to Q-Learning 🎲

In this unit, I coded my first tabular **Q-Learning** algorithm from scratch using NumPy and Gymnasium to solve value-based environments like `FrozenLake-v1` and `Taxi-v3`.

---

## 🎮 Environments & Algorithm

- **Environments:** `FrozenLake-v1` ⛄ and `Taxi-v3` 🚕 (Gymnasium)
- **Algorithm:** Q-Learning (Tabular)
- **Library:** Python, NumPy, Gymnasium

---

## 🧠 Key Concepts Practiced

- **Q-Table Initialization & Updates:** Building and updating a state-action lookup table using the Bellman equation.
- **Epsilon-Greedy Policy:** Balancing exploration (random action selection) and exploitation (choosing max Q-value).
- **Off-Policy RL:** Understanding the difference between acting policy ($\epsilon$-greedy) and updating policy (greedy).
- **Hyperparameter Decay:** Decreasing $\epsilon$ exponentially over time to move from exploration to optimal action selection.

---

## 📊 Training Results & Metrics

- **Taxi-v3 Pass Threshold:** Target score $\ge 4.5$ ($\text{Mean Reward} - \text{Std Reward}$)
- **Evaluated Episodes:** 100

---

## 🎥 Agent Demo & Model Card

- [Hiten1896/q-Taxi-v3](https://huggingface.co/Hiten1896/q-Taxi-v3)
