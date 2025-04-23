# CS370-TreasureHunt-AI-Pirate-Intelegent-Agent

# Pirate Maze Agent – Deep Q-Learning Pathfinding Project

This project showcases the development of a reinforcement learning agent (an AI-controlled pirate) trained to solve a maze by reaching a treasure before a human player. It was built using Python, Keras, and a custom maze environment within a Jupyter Notebook environment as part of a reinforcement learning course.

## Project Overview

The core challenge was to train an intelligent agent using deep Q-learning, a technique that allows the pirate to learn from experience and optimize its decision-making over time. The maze environment was structured as an 8x8 grid with pathways and obstacles. The agent began with no knowledge of the environment and had to learn the most efficient path to the goal (the treasure) by balancing exploration and exploitation.

### Code Breakdown

- **Provided Code**: 
  - The `TreasureMaze.py` file which defines the environment logic.
  - The `GameExperience.py` file which handles the replay buffer (experience storage).
  - Skeleton functions and helper methods within a Jupyter Notebook (e.g., maze setup, visualization).
  
- **My Contributions**: 
  - Implemented the core `qtrain()` function to handle agent training using deep Q-learning.
  - Tuned hyperparameters such as `epsilon`, `max_memory`, and training epochs.
  - Added logic for exploration/exploitation via ε-greedy policy.
  - Managed early stopping conditions, model saving, and win rate tracking.
  - Improved clarity with extensive in-line comments and debugging.
  - Wrote a full design defense explaining the AI approach and how the model works.

## Reflections on Learning

### What I Learned and Created

This project solidified my understanding of reinforcement learning, neural networks, and how they can be applied to real-world pathfinding problems. I learned how to build an agent that improves over time, stores past experiences, and makes predictions using a neural network. I also strengthened my skills in Python, machine learning logic, and data-driven decision-making.

### Connecting to the Field of Computer Science

**What do computer scientists do and why does it matter?**  
Computer scientists solve problems using structured, logical thinking and code. Whether improving a game AI, analyzing data, or securing systems, they design efficient, ethical solutions that impact real lives. This matters because computing powers everything from healthcare to entertainment to finance.

**How do I approach a problem as a computer scientist?**  
I approach problems by breaking them down into smaller components, identifying known patterns or algorithms, and iterating on solutions with data-backed feedback. In this project, that meant using reward-based learning, tuning parameters, and debugging training loops to improve the pirate’s performance.

**What are my ethical responsibilities to the end user and organization?**  
My responsibility is to create systems that are reliable, transparent, fair, and respectful of user privacy and safety. In AI, especially, ethical considerations include avoiding biased learning, ensuring models behave predictably, and understanding the long-term consequences of automation.

## How to Run This Project

1. Download all project files from this repository:
   - `TreasureHuntGame.ipynb`
   - `TreasureMaze.py`
   - `GameExperience.py`
2. Open the `.ipynb` file in Jupyter Notebook.
3. Run the cells in order to build, train, and test the pirate agent.
4. You can modify training parameters in the `qtrain()` function to experiment with learning behavior.

---

This project is part of my reinforcement learning and machine learning portfolio. It demonstrates my ability to apply key AI concepts to solve practical problems. Feel free to explore the code, test different maze setups, or build on the agent logic.
