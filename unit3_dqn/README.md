# Unit 3: Deep Q-Learning (DQN) with Atari Games 👾

In this unit, I trained a **Deep Q-Network (DQN)** using Convolutional Neural Networks to process raw pixel observations and master Atari environments like `SpaceInvadersNoFrameskip-v4`.

---

## 🎮 Environment & Algorithm

- **Environment:** `SpaceInvadersNoFrameskip-v4` 🚀
- **Algorithm:** Deep Q-Network (DQN)
- **Libraries:** `RL Baselines3 Zoo` / `Stable-Baselines3`, Gymnasium, PyTorch

---

## 🧠 Key Concepts Practiced

- **Temporal Difference Learning with Neural Nets:** Replacing tabular lookup with deep function approximation for complex visual state spaces.
- **Frame Stacking & Preprocessing:** Converting RGB frames to grayscale, cropping, and stacking 4 consecutive frames to capture velocity and motion context.
- **Experience Replay Buffer:** Storing past transitions $(s, a, r, s')$ and sampling random batches to break temporal correlations between successive steps.
- **Fixed Target Network:** Decoupling action selection from action evaluation using a separate target model to stabilize gradient updates.

---

## 📊 Training Results & Metrics

- **Mean Reward:** **262.00 ± 140.56**
- **Target Threshold:** >= 200 (Pass threshold for course certification)
- **Training Timesteps:** 1,000,000

---

## 🎥 Agent Demo & Model Card

Check out the live model card and video preview on Hugging Face:

👉 **[Hiten1896/dqn-SpaceInvadersNoFrameskip-v4](https://huggingface.co/Hiten1896/dqn-SpaceInvadersNoFrameskip-v4)**
