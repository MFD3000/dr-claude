# dr-claude

<img src="images/DrClaude.jpeg" width="128">

A Next Best Action Engine to help healthcare professionals "pathfind" towards the most accurate diagnosis in the shortest possible time, optimizing patient outcomes and resource utilization. Combines the power of symbolic reasoning (AlphaGo-style MCTS) with LLMs (Dr Claude contextualization) and retrievals.

We use a [Disease-Symptom Knowledge Database](https://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html) for Dr Claude to reason over.

## 1. Getting Started

We're using [Poetry](https://python-poetry.org/docs/) for managing dependencies.


Run `poetry install` to install dependencies, then `make app` to start the engine.

<img src="images/demo.png" width="780">
