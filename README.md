# 🐍 Snake Game – Automation via Reinforcement Learning

This project implements the classic Snake Game and trains an agent to play it using **Deep Q-Learning** (a type of Reinforcement Learning). The agent learns to improve over time by interacting with the game environment and maximizing its score using feedback in the form of rewards.


## 🚀 Project Highlights

- 🎮 Snake Game implemented using **Pygame**
- 🧠 Agent powered by **Deep Q-Network (DQN)**
- 📈 Learns through **Experience Replay** and **Short/Long-Term Memory**
- 📦 Modular code split into environment, agent, model, and helper files


## 🧱 Project Structure

📁 SNAKE-Game-Automation-Reinforcement_Learning

SNAKE-Game-Automation-Reinforcement_Learning/

├── agent.py # Reinforcement Learning agent logic

├── game.py # Snake game environment

├── helper.py # Utility functions

├── model.py # Neural Network architecture

├── snake_game_human.py # Play Snake manually (for testing)

├── arial.ttf # Font for game rendering

├── model/ # Trained models (saved checkpoints)

├── pycache/ # Ignored by Git (bytecode)

└── README.md # You are here


## 🧠 Learning Algorithm

The agent is trained using **Deep Q-Learning** with the following key ideas:

- **State Representation**: Position of snake, direction, food, and potential dangers
- **Action Space**: [straight, right turn, left turn]
- **Reward Function**:
  - `+10` for eating food  
  - `-10` for hitting a wall or self  
  - `0` otherwise
- **Experience Replay**: Uses past experiences to break correlation and improve stability
- **Epsilon-Greedy Strategy**: Balances exploration and exploitation


## 🛠️ Installation & Setup

1. Clone the repository:
   git clone https://github.com/Shubhasish01/SNAKE-Game-Automation-Reinforcement_Learning.git
   cd SNAKE-Game-Automation-Reinforcement_Learning
   
Install dependencies:
pip install -r requirements.txt

Train the agent:
python agent.py

Play manually:
python snake_game_human.py

📌 TODOs & Future Work
 Add support for saving/loading models

 Visualize Q-values in real-time

 Experiment with other RL algorithms (e.g., PPO, A3C)

🤝 Contributions
Feel free to fork the repo, improve the code, and submit a pull request!

📜 License
MIT License. See LICENSE file for details.

🙋‍♂️ Author
Shubhasish
GitHub Profile
