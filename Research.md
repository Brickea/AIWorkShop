# Research about RL in Stock Prediction

## Critical Problem:

1. Create a python notebook that develops a stock price predictive model using Reinforcement Learning, python and TensorFlow.

* Whicn kind of RL model needed to be built to model stock price prediction
* Which kind of TensorFlow APIs will been used in building RL model
* How evaluate the prediction model
* How to extract data

2. Plan

* Main RL Model:
    * Q-Learning
    * Deep Q-network(DQN)
    * Policy Model
    * LSTM

## RL Syllabus

[Medium Reinforcement Learning](https://towardsdatascience.com/november-edition-deep-learning-6d97357a975b)

[Reinforcement Learning](https://deeplizard.com/learn/video/nyjbcRQ-uQ8)

* Part 1: Introduction to Reinforcement Learning
    * Section 1: Markov Decision Processes (MDPs)
        * Introduction to MDPs
        * Policies and value functions
        * Learning optimal policies and value functions
    * Section 2: Q-learning
        * Introduction to Q-learning with value iteration
        * Implementing an epsilon greedy strategy
    * Section 3: Code project - Implement Q-learning with pure Python to play a game
        * Environment set up and intro to OpenAI Gym
        * Write Q-learning algorithm and train agent to play game
        * Watch trained agent play game
* Part 2: Deep Reinforcement Learning
    * Section 1: Deep Q-networks (DQNs)
        * Introduction to DQNs
        * Experience replay
    * Section 2: Code project - Implement deep Q-network with PyTorch to play a game
        * Environment set up
        * Create and train DQN to play game
        * Watch trained DQN play game
    * Section 3: Policy gradients
        * More details to come

## Tensorflow RL Tutorial

[Simple Reinforcement Learning with Tensorflow](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)

* Part 0 — Q-Learning Agents
* Part 1 — Two-Armed Bandit
* Part 1.5 — Contextual Bandits
* Part 2 — Policy-Based Agents
* Part 3 — Model-Based RL
* Part 4 — Deep Q-Networks and Beyond
* Part 5 — Visualizing an Agent’s Thoughts and Actions
* Part 6 — Partial Observability and Deep Recurrent Q-Networks
* Part 7 — Action-Selection Strategies for Exploration
* Part 8 — Asynchronous Actor-Critic Agents (A3C)

## Stock Theory

[Stock prediction](https://en.wikipedia.org/wiki/Stock_market_prediction)

## How to extract sDataset

* Use stock API from [AlphaVantage](https://www.alphavantage.co/documentation/).

* You can use the code in this [notebook](https://github.com/ninadsubhedar/StockPredictionWithLSTM/blob/master/StockPricePredictionWithLSTM.ipynb) to grab the data.

### 1. API Key

Welcome to Alpha Vantage! Your API key is: ```G6JDX3PTNITW8EW1```. Please record this API key for future access to Alpha Vantage.