# Project 2: Multi-Agent Search - Pacman Maze

## Introduction
In this project, I've designed agents for the classic version of Pacman, including ghosts. Along the way, I implemented both minimax and expectimax search algorithms and tried my hand at designing evaluation functions.

## How to Use and Clone
1. **Cloning the Repository:**
   - Clone the assignment repository using the provided GitHub Classroom link.
   - Open a terminal and run the following command:
     ```
     git clone https://github.com/shakir-flash/Pacman-AI-Multi-Agent-Search.git
     ```

2. **Running Pac-Man:**
   - Navigate to the cloned directory.
   - Change directory to the `multiagent` folder.
   - Run Pac-Man using the following command:
     ```python
     python pacman.py
     ```

## Instructions
- Use the provided `multiAgents.py` file to implement multi-agent search algorithms.
- The code base includes an autograder for grading your answers on your machine. It can be run on all questions with the command:
```python
python autograder.py
```
- For running on a specific question, use:
```python
python autograder.py -q [question_number]
```


## Complete Details of All Search Algorithms

### Question 1: Reflex Agent
- **Description:** Improve the `ReflexAgent` to play respectably by considering both food locations and ghost locations.

### Question 2: Minimax
- **Description:** Write an adversarial search agent in the `MinimaxAgent` class stub. The agent should work with any number of ghosts and expand the game tree to an arbitrary depth.

### Question 3: Alpha-Beta Pruning
- **Description:** Implement an agent using alpha-beta pruning in the `AlphaBetaAgent` class. Extend the alpha-beta pruning logic appropriately to multiple minimizer agents.

### Question 4: Expectimax
- **Description:** Implement the `ExpectimaxAgent` to model probabilistic behavior of agents who may make suboptimal choices.

### Question 5: Evaluation Function
- **Description:** Write a better evaluation function for Pacman in the `betterEvaluationFunction` function. The evaluation function should evaluate states rather than actions.

## Summary
In this project, I've delved into the realm of multi-agent search algorithms to equip Pacman with better decision-making abilities. By implementing algorithms like minimax, alpha-beta pruning, and expectimax, and designing an effective evaluation function, I've empowered Pacman to navigate complex mazes filled with ghosts.
