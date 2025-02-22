# 🐦 Flappy Bird AI

Welcome to **Flappy Bird AI**! 🎮 This project uses the **NEAT (NeuroEvolution of Augmenting Topologies) algorithm** to train an AI to play Flappy Bird. The AI evolves over generations to improve its gameplay.

## 📂 Project Structure
```
Flappy Bird AI/
├── imgs/               # Contains all the images necessary to render the game
│   ├── bse.png
│   ├── bg.png
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.py
├── requirements.txt    # Dependencies
├── .gitignore          # Git ignored files
├── config.txt          # Contains necessary parameters for the NEAT algorithm
├── game.py             # Main game file
└── README.md           # Project documentation
```

## 🚀 Features
- Uses **NEAT algorithm** to evolve AI for playing Flappy Bird 🤖
- AI learns from its mistakes and improves over generations
- Dynamic gameplay with animated bird and pipes 🎨
- Configurable parameters via `config.txt` 🛠️

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/palassaha/Flappy-Bird-AI.git
cd Flappy-Bird-AI
```

### 2️⃣ Create & Activate Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Game
```sh
python game.py
```

## 🤖 How the AI Works
1. The game starts with multiple AI-controlled birds.
2. Each bird has a **neural network** controlling its decisions.
3. The NEAT algorithm selects the best-performing birds and evolves them over generations.
4. Over time, the AI learns to navigate the pipes efficiently.

## ⚙️ Configuration
Modify `config.txt` to adjust NEAT parameters such as:
- **Population size**
- **Mutation rates**
- **Fitness function parameters**

## 🏆 Goal
The AI's goal is to achieve the highest possible score by avoiding pipes and staying airborne.

---
Made with ❤️ for AI and gaming enthusiasts! 🎮