
# Seeded LDA for Grievance Mechanism Analysis

This project applies **Seeded Latent Dirichlet Allocation (LDA)** to analyze corporate disclosures on grievance mechanisms, whistleblowing, and supply chain reporting.  
It uses predefined seed keywords to guide topic modeling and improve interpretability.  

## Contents
- `SEEDED_LDA_Grievance_1.ipynb` – Main Colab notebook with preprocessing, modeling, and analysis.
- `document_topic_distributions.csv` – Document-topic probability distributions.
- `lda_interactive_visualization.html` – Interactive pyLDAvis visualization of topics.
- `requirements.txt` – Python dependencies.

## Features
- Text preprocessing (NLTK-based tokenization, lemmatization, stopword removal).
- Seeded LDA modeling with Gensim.
- Topic coherence evaluation.
- Word clouds and topic distribution plots.
- Interactive pyLDAvis visualization.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/rozaghaedi/Seeded-LDA-Grievance.git
cd Seeded-LDA-Grievance
pip install -r requirements.txt

```

---
## Usage

1- Open the Jupyter/Colab notebook:

``` jupyter notebook SEEDED_LDA_Grievance_1.ipynb```


2- Run the cells to preprocess text, train the model, and view results.

3- Explore topics interactively in lda_interactive_visualization.html.
