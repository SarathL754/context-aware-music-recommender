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
**Song labels**
Zero-shot prompt designed for Mistral-7B to classify song lyrics into one of four predefined mood categories. The model is instructed to return only the most suitable mood enclosed within [ANS] tags for consistent parsing
<img width="1298" height="358" alt="image" src="https://github.com/user-attachments/assets/ebc8ae5c-95d1-4284-9c72-cba8ec99a36f" />

Distribution of Predicted Mood Labels from Mistral-7B
The majority of lyrics were classified as Uplifting and motivational, followed by Sadness or melancholy. Few tracks were labeled as Social gatherings or parties, and a small number were marked as unknown due to ambiguous or empty lyrics.
<img width="1516" height="911" alt="image" src="https://github.com/user-attachments/assets/9db8e480-4282-4fbe-b904-dd935811c153" />


**Knowledge Graph**
<img width="821" height="301" alt="image" src="https://github.com/user-attachments/assets/554956b7-fed1-4038-ba70-c3a2af58e0a9" />

Snapshot showing the total number of nodes and edges in the constructed Knowledge Graph, along with sample semantic edges. The graph encodes user preferences (e.g., user_20-35_Female → Relaxation and stress relief) and mood-to-song associations (e.g., Relaxation and stress relief → 04J7j9wIMuE8wASt1evdKv), forming the basis for explainable and mood-aligned recommendation paths.

<img width="957" height="823" alt="image" src="https://github.com/user-attachments/assets/be6cad23-ae94-4020-8acf-fa62a7de4e47" />
Sample subgraph from the full Knowledge Graph (KG), showing connections between users, moods, and songs. The graph captures 2-hop paths like User → Mood → Song, forming the environment for the RL agent to traverse. Nodes are color-coded and labeled for interpretability.





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
