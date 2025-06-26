# Adaptive Social Media Agent

This project simulates an adaptive reinforcement learning agent that optimizes social media content strategies. It uses Q-learning with a novelty reward to balance follower growth, content diversity, and user engagement. Inspired by Ashby’s principles of ultrastability, the system models adaptive behavior in dynamic environments.

## 📌 Project Objectives
- Model a personal branding/content strategy system with feedback from simulated followers
- Apply Q-learning to learn optimal posting strategies
- Integrate a novelty search component to promote content exploration and behavioral diversity
- Analyze system adaptability using state-action tracking, heatmaps, and behavioral clustering

## 🧠 Core Features
- Reinforcement learning agent with Q-learning
- Novelty buffer to track and reward diverse behavior
- Social media simulation environment with dynamic user feedback
- Statistical analysis: rewards, novelty trends, and agent behavior over time
- Robustness testing through reward noise and multiple random seeds

## 🛠️ Technologies Used
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (for PCA and clustering)
- OpenAI Gym-style environment (custom implementation)

## 📈 Experiments & Analysis
- Ensemble runs with multiple seeds
- Noise-injected reward signals
- Novelty evolution graphs
- Clustering of state-action trajectories
- t-SNE/UMAP visualizations

## 📁 Repository Structure
