# Inconsistency Detection in Cancer Data Classification Using Explainable AI

This repository contains the code and resources for the project **"Inconsistency Detection in Cancer Data Classification Using Explainable AI"**. The project focuses on identifying inconsistencies in cancer data classifications by leveraging explainable artificial intelligence (AI) techniques.

[Preprint: Inconsistency Detection in Cancer Data Classification Using Explainable AI](https://www.medrxiv.org/content/10.1101/2024.10.02.24314783v1)

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Introduction

Accurate classification of biomedical literature is crucial for effective information retrieval and knowledge discovery in cancer research. This project aims to detect inconsistencies in cancer data classification by applying explainable AI methods, providing insights into the decision-making process of machine learning models.

## Dataset

The dataset used in this project is publicly available on Kaggle:

- [Biomedical Text Publication Classification Dataset](https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification)

This dataset comprises biomedical text publications categorized for classification tasks.

## Installation

To set up the project environment, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/pouriamrt/cancer_inconsistency.git
   cd cancer_inconsistency
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

   Ensure that you have Python 3.6 or higher installed.

## Usage

The project includes several Jupyter notebooks that demonstrate different aspects of the analysis:

- `BERTopic_N2V_ML.ipynb`: Topic modeling using BERTopic and Node2Vec.
- `Classification.ipynb`: Initial classification experiments.
- `Classification_opt2.ipynb`: Optimized classification approaches.
- `Intersection_ml_bert_human.ipynb`: Analysis of intersections between machine learning, BERT embeddings, and human annotations.
- `Recommender_Optimization.ipynb`: Optimization of recommender systems.
- `doc2vec_withoutgraph.ipynb`: Document embedding without graph structures.

To run these notebooks:

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open the desired notebook and execute the cells sequentially.**

## Project Structure

```
cancer_inconsistency/
│
├── BERTopic_N2V_ML.ipynb          # Topic modeling using BERTopic and Node2Vec
├── Classification.ipynb           # Initial classification experiments
├── Classification_opt2.ipynb      # Optimized classification approaches
├── Intersection_ml_bert_human.ipynb # Intersections between ML, BERT, and human annotations
├── Recommender_Optimization.ipynb # Recommender system optimization
├── doc2vec_withoutgraph.ipynb    # Document embedding without graphs
├── KG_with_menu.html              # Interactive knowledge graph visualization
├── KG_subgraph_with_menu.html     # Subgraph with interactive features
├── requirements.txt               # Required Python packages
└── LICENSE                        # Project license
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request. Ensure that your contributions align with the project's objectives and maintain code quality.

## License

This project is licensed under the [MIT License](LICENSE).

## References

- [Preprint: Inconsistency Detection in Cancer Data Classification Using Explainable AI](https://www.medrxiv.org/content/10.1101/2024.10.02.24314783v1)
- [Biomedical Text Publication Classification Dataset](https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification)

For any questions or further information, please contact the repository owner.
