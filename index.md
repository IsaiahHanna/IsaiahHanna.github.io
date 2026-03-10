# Portfolio
---
### Parameter-Efficient Fine-Tuning of Qwen2.5-VL for Hazard-Aware VQA in Urban Environments
[![Project Proposal](https://img.shields.io/badge/PDF-Project_Proposal-red?logo=adobeacrobatreader)](https://isaiah-jqe0wb.filedrop.me/s/4da0f0b8-0c56-40c5-95a6-7770cc25ab5d)

Visual Question Answering (VQA) has proven to be a useful tool in semantic risk detection and replanning by providing vehicles with the capability to answer natural language questions about the environment. In this project, I'll use HuggingFace's transformers library to fine-tune a Qwen2.5-VL model for vulnerable road user (VRU) intent prediction. I will then compare the fine-tuned model’s performance against ground-truth labels and a baseline Qwen2.5-VL-3B model without task-specific fine-tuning.



---
### Sentiment and Performance Modeling of Property Listings


Sentiment analysis and predictive modeling can help uncover the drivers of customer satisfaction in large-scale online marketplaces by extracting insights from user-generated text and structured listing data. In this project, I analyze 250,000 Airbnb listings and millions of guest reviews using R, tidytext, and ranger to model the factors influencing guest satisfaction and property performance. I generate sentiment scores and perform amenity-focused text analysis to measure how specific amenities affect review sentiment, then engineer predictive features and train machine learning models to identify and rank listings most likely to achieve high guest satisfaction.

---
### Deep Reinforcement Learning Implementations
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/IsaiahHanna/RLImplementations)

Deep reinforcement learning algorithms enable agents to learn optimal decision-making policies through interaction with an environment. In this project, I implement several foundational deep RL algorithms, including Deep Q-Networks (DQN), Advantage Actor-Critic (A2C), and Vanilla Policy Gradient (REINFORCE), from scratch using PyTorch and OpenAI Gym. The implementations emphasize clarity and modular design while demonstrating key concepts such as temporal-difference learning, policy gradients, actor–critic architectures, and experience replay, creating a clean experimental framework for studying and extending modern reinforcement learning methods.


---
### Tabular Reinforcement Learning

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/IsaiahHanna/FrozenLake)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/IsaiahHanna/Gridworld)

Tabular reinforcement learning provides a foundation for understanding how agents learn optimal policies through interaction with an environment. In this project, I implement and analyze classic RL methods, SARSA and Q-learning, in both OpenAI Gym’s FrozenLake environment and a custom-built Gridworld maze created with PyGame. The work explores key concepts such as temporal-difference learning, on-policy vs. off-policy control, ε-greedy exploration, and environment stochasticity, while demonstrating how agents learn optimal navigation policies using tabular Q-value updates in both standard benchmark environments and custom simulations.
<br>
<center><img src="images/gridworld.gif"/></center>
<br>

---
### Mock SQL Trading System

Relational database systems can enforce complex financial constraints while maintaining data integrity and efficient query performance. In this project, I design and implement a brokerage trading system using SQL and PostgreSQL, defining normalized tables, relationships, and constraints to model accounts, brokers, and trades. I implement PL/pgSQL triggers to enforce key business rules such as append-only trade records, sequential trade ordering, and restrictions preventing brokers from owning accounts. Additionally, I create a dynamic Holds view that computes portfolio holdings directly from trade history while validating trades to prevent overselling.


---
### EM-Based Recommender


[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/IsaiahHanna/EM-Based-Recommender)

Probabilistic models can capture latent user preferences in recommender systems even when rating data is sparse or incomplete. In this project, I implement a collaborative filtering recommender using a mixture of Gaussians trained with the Expectation–Maximization (EM) algorithm on a sparse Netflix movie ratings matrix. The model learns latent user-type distributions through soft clustering and handles missing data during training, then predicts unseen ratings by computing conditional expectations under the learned mixture model, demonstrating how probabilistic inference can improve matrix completion and recommendation accuracy.


---
### AnimeRecommendation

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/IsaiahHanna/AnimeRecommendation)

Content-based recommendation systems can identify similar items by comparing structured metadata and feature representations. In this project, I build a productionized anime recommender that maps a user’s favorite show to similar titles using a Nearest Neighbors similarity search implemented with scikit-learn. I collect and curate anime metadata through the MyAnimeList API, constructing a structured dataset that powers the similarity engine, and deploy the model in a Flask web application with a form-driven interface that returns recommendations through a clean web UI.

---
### Risk App Proposal


Geospatial data analysis can support decision-making tools that help communities respond to natural disasters. In this project, developed during the 2024 Business Analytics Hackathon, I analyze Vancouver geospatial risk data using Python to construct a composite risk score and identify areas of vulnerability following a disaster event. I then create interactive visualizations in Tableau to communicate insights and propose app features designed to help residents locate resources and assess risk in real time. The project was presented to industry judges and selected as a top-five finalist among twenty-five competing teams.

