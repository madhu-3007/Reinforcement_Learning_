# Smart Hospital Medicine Delivery Robot

## Overview

This project uses **Reinforcement Learning** to help a hospital robot find the best path from the pharmacy to the patient while avoiding obstacles.

## Algorithms Used

* Q-Learning
* SARSA

## Dataset

Dataset used:

`hospital_navigation_dataset.csv`

It contains:

* Row
* Column
* Cell Type
* Reward

## Reward System

* Goal: +100
* Normal move: -1
* Obstacle: -10
* Outside grid: -5

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Google Colab

## Project Workflow

1. Load the dataset.
2. Create the hospital environment.
3. Set start, goal, and obstacles.
4. Train the Q-Learning model.
5. Train the SARSA model.
6. Compare both models.
7. Display the best path.

## Files

* `Hospital_Reinforcement_Model.ipynb`
* `hospital_navigation_dataset.csv`
* `README.md`

## Output

The project displays:

* Reward graphs
* Success rate
* Average steps
* Q-Learning path
* SARSA path
* Best performing model

## Conclusion

The project shows how **Q-Learning and SARSA** can be used to train a hospital medicine delivery robot to reach a patient safely and efficiently.
