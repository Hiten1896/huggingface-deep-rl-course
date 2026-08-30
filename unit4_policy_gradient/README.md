# Unit 4: Policy Gradient with PyTorch 🚀

In this unit, I built and trained a Policy Gradient agent from scratch using PyTorch to solve both the CartPole and Pixelcopter environments using the REINFORCE algorithm.

---

## 🎮 Environment & Algorithm

- **Environments:** `CartPole-v1` & `Pixelcopter-PLE-v0` (Gymnasium)
- **Algorithm:** REINFORCE (Monte Carlo Policy Gradient)
- **Library:** `PyTorch`

---

## 🧠 Key Concepts Practiced

- **Policy Networks:** Approximating action probabilities directly using neural networks rather than value functions.
- **Trajectory Sampling:** Collecting entire episodes of states, actions, and rewards to calculate cumulative discounted returns.
- **Log Probabilities & Loss:** Scaling policy gradients using trajectory returns to reinforce actions that led to high rewards.
- **Hugging Face Hub Integration:** Uploading the trained PyTorch policy weights and evaluation metrics directly to the Hub.

---

## 📊 Training Results & Metrics

- **CartPole-v1 Mean Reward:** **403.20 ± 193.60**
- **Pixelcopter-PLE-v0 Mean Reward:** **377.20 ± 197.35**
- **Target Threshold:** Pass threshold for course certification
- **Training Episodes:** 1,000

---

## 🎥 Agent Demo & Model Card

Check out the live model cards and video previews on Hugging Face:
👉 **[Hiten1896/reinforce-CartPole-v1](https://huggingface.co/Hiten1896/reinforce-CartPole-v1)**
👉 **[Hiten1896/reinforce-Pixelcopter-PLE-v0](https://huggingface.co/Hiten1896/reinforce-Pixelcopter-PLE-v0)**
