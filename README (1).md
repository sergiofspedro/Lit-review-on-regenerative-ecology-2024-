# Literature Review – Regenerative Ecology (2024)

This repository contains the Jupyter Notebook **`Lit review_regenerative ecology_2024.ipynb`**, which performs a structured literature review and exploratory analysis on regenerative ecology research. The notebook uses the [**litstudy**](https://pypi.org/project/litstudy/) package and common Python data-analysis tools to collect, analyze, and visualize bibliographic data related to regenerative design and net-positive ecology.

## 📋 Overview
The notebook includes:
- **Dataset Collection**: Uses `litstudy` to search, retrieve, and structure bibliographic datasets on regenerative ecology.
- **General Statistics**: Summarizes publication counts, trends over time, and citation metrics.
- **Network Analysis**: Builds co-authorship or keyword co-occurrence networks to identify key contributors and research clusters.
- **Topic Modeling**: Applies topic modeling (basic and advanced) to uncover thematic structures within the literature.
- **Visualization**: Generates graphs and plots using `matplotlib` and `seaborn` for clearer insights.

## 🛠️ Dependencies
Key Python packages:
- `litstudy`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

Install all dependencies with:
```bash
pip install litstudy numpy pandas matplotlib seaborn
```

## ▶️ Usage
1. Open the notebook:
   ```bash
   jupyter notebook "Lit review_regenerative ecology_2024.ipynb"
   ```
2. Follow the sections in order:
   - **Imports** → **Collecting the dataset** → **General statistics** → **Network analysis** → **Topic modeling**.
3. Modify search queries or parameters within the **Collecting the dataset** cell to focus on different subtopics of regenerative ecology.

## 📊 Output
- Publication trend plots (yearly counts).
- Network graphs of co-authors or keywords.
- Topic distributions and top terms for each topic.
- Tables summarizing dataset statistics.

## 🌿 Purpose
This notebook supports research in regenerative ecology and regenerative design by:
- Identifying leading authors, institutions, and themes.
- Mapping the evolution of regenerative ecology scholarship.
- Providing a reproducible pipeline for literature review and topic modeling.

## 📄 License
Specify your preferred license here (e.g., MIT, CC-BY).

---
*Created: 2024 – Updated for clarity in 2025.*
