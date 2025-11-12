# CE6020 Assignment 3 - Reinforcement Learning

Train an agent to play customized TaxiV3 game from Gymnasium.

This is the Assignment 3 of CE6020 Artificial Intelligence class NCU Fall 2025 taught by Prof. Chia-Hui Chang.

![taxi](./images/taxi.gif)
\* Image is for illustration only

 ## Task Description

Taxi Game : 

At the beginning of the game, the taxi appears randomly anywhere on the map, while the passenger only appears at one of the four fixed locations(R, G, Y ,B).The destination is also one of these four locations, but it will never be the same as the passenger's initial location.The goal is to pick up the passenger and transport them to the destination.

Environment : 

Map : 5x5 grid world with 3 random map configurations.
Four Locations : Red(R), Green(G), Yellow(Y), Blue(B).
Weather Condition : Rainy mode(is_rainy=True), 20% chance of slipping in unintended directions

 ## Notebook

Code implementation can be accessed in [Google Colab](https://colab.research.google.com/drive/1z3DmCZXYDetmPsErKHi5iaOALC1rV-br?usp=sharing).

`notebook` folder contains baseline notebook and other experiments
- `Assignment3.ipynb` -> baseline code
- `Assignment3_actionmask_exp.ipynb` -> experiments on action mask
- `Assignment3_actorcritic.ipynb` -> experiments on actor critic

 
 ## How to Run

The main code is `main.ipynb` which was based on the baseline notebook provided from the class.

You can create Copy & Edit of the notebook directly on Google Colab or you can run locally. This code was run on Python v3.11.

If you want to run locally, it is recommended to use venv.

Create new python virtual environment.

`python3 -m venv .venv`

Activate venv

`source .venv/bin/activate` for Linux; or 

`.\venv\Scripts\activate` for Windows 

Install dependencies such as PyTorch, sklearn, transformers, seaborn.


