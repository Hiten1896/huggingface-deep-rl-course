# Unit 1: Introduction to Deep Reinforcement Learning 🤖

In this unit, I trained my first Deep Reinforcement Learning agent to land safely on the moon using **Proximal Policy Optimization (PPO)**.

---

## 🎮 Environment & Algorithm

- **Environment:** `LunarLander-v2` (Gymnasium Box2D)
- **Algorithm:** PPO (Proximal Policy Optimization)
- **Library:** `Stable-Baselines3`

---

## 🧠 Key Concepts Practiced

- **Markov Decision Processes (MDPs):** States, actions, rewards, and transitions.
- **Policy vs. Value Methods:** Understanding policy distributions and value function estimation.
- **Vectorized Environments:** Running parallel environments (`make_vec_env`) to collect diverse training experiences.
- **Hugging Face Hub Integration:** Exporting trained agent weights and evaluation metadata directly to HF Hub.

---

## 📊 Training Results & Metrics

- **Mean Reward:** [$254.08 \pm 29.32$]
- **Target Threshold:** >= 200 (Pass threshold for certification)
- **Training Timesteps:** 1,000,000

---

## 🎥 Agent Demo

*(Hiten1896/ppo-LunarLander-v2)*
