# Context-Aware Music Recommender

A research project that combines **Knowledge Graphs** and **Reinforcement Learning** to build a mood-based music recommendation system.

## Overview

This project was developed as part of the Summer Research Program 2025 at the University of North Texas (UNT).
This project explores how knowledge graphs can model relationships between songs, moods, artists, and other contextual factors, while reinforcement learning is used to optimize personalized music recommendations based on user mood and behavior.

## Features

- **Knowledge Graph Construction**: Model entities like songs, artists, moods, and their relationships.
- **Context Awareness**: Incorporate user mood and context for personalized recommendations.
- **Reinforcement Learning**: Learn optimal recommendation strategies through user feedback.
- **Data Exploration**: Jupyter Notebooks for interactive analysis and experimentation.

## Tech Stack

- **Jupyter Notebook** (100%)
- Python (recommended for graph and RL libraries such as NetworkX, PyTorch, etc.)
- Knowledge Graph libraries (e.g., RDFLib, NetworkX)
- Reinforcement Learning frameworks (e.g., stable-baselines3, OpenAI Gym)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SarathL754/context-aware-music-recommender.git
   cd context-aware-music-recommender
   ```

2. **Set up the environment:**
   - It is recommended to use a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     ```
   - Install dependencies (add your requirements to `requirements.txt`):
     ```bash
     pip install -r requirements.txt
     ```

3. **Open the notebooks:**
   - Launch Jupyter Lab or Notebook:
     ```bash
     jupyter lab
     # or
     jupyter notebook
     ```

## Usage

- Run and explore the Jupyter Notebooks for:
  - Knowledge graph creation and visualization
  - Mood/contextual data modeling
  - Reinforcement learning experiments for recommendation

## Example

<!-- Add screenshots or usage examples if available -->

```
# Example: Loading a knowledge graph and making a mood-based recommendation
# [Insert code snippet or notebook cell here]
```

## Project Structure

```
context-aware-music-recommender/
├── notebooks/               # Jupyter Notebooks for experiments and analysis
├── data/                    # (Optional) Datasets used for building graphs and training
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Author

[SarathL754](https://github.com/SarathL754)
