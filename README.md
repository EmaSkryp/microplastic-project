Medium Article : https://medium.com/@youssifhebesha123/words-and-wisdom-7a216b902943 



Stylometric Analysis of Jane Austen

Course: Applied NLP
Texts: Pride and Prejudice (1813) and Sense and Sensibility (1811)
Author: Jane Austen

⸻

Project Overview

This project applies Natural Language Processing (NLP) methods to explore and compare the writing style of Jane Austen across two of her novels: Pride and Prejudice and Sense and Sensibility. Inspired by stylometric approaches discussed in class, the project asks:

What can computational methods reveal about differences in style within the works of a single author?

Rather than focusing on themes or plot, the analysis examines sentence-level structure, readability, semantic drift, and paragraph-level functions to uncover subtle stylistic variation between the two novels.

⸻

Corpus
	•	Pride and Prejudice (1813)
	•	Sense and Sensibility (1811)

Both texts are:
	•	Written in English
	•	In the public domain
	•	Sourced from Project Gutenberg
	•	Substantial in size (each exceeding 50,000 words)

⸻

Methods & Notebooks

The analysis is organized into four Jupyter notebooks, each focusing on a different linguistic level:

1. Sentence Length Analysis

Notebook: 1_AppliedNLP_Session3_Sentence_Length.ipynb
	•	Sentence tokenization
	•	Distribution of sentence lengths
	•	Mean and variance comparison
	•	Visualization of sentence length histograms

This analysis highlights differences in narrative pacing and syntactic complexity between the two novels.

⸻

2. Readability Analysis

Notebook: 2_AppliedNLP_Session3_Readability.ipynb
	•	Flesch Reading Ease
	•	Flesch–Kincaid Grade Level
	•	Comparison of readability scores

Readability metrics provide insight into how accessible or complex the prose is across the two works.

⸻

3. Topic Drift Analysis

Notebook: 2_AppliedNLP_Session4_Topic_Drift.ipynb
	•	Sentence embeddings using transformer models
	•	Measurement of semantic change across narrative progression
	•	Visualization of topic drift patterns

This notebook explores how semantic focus shifts over the course of each novel.

⸻

4. Paragraph Function Classification

Notebook: 5_AppliedNLP_Session4_Paragraph_Function_Classification.ipynb
	•	Paragraph segmentation
	•	Embedding-based similarity
	•	Classification into functional categories (e.g., narration, dialogue, reflection)

This analysis examines structural and functional differences in how paragraphs are used across the two novels.

⸻

Key Findings (Summary)
	•	Sense and Sensibility consistently uses longer and more variable sentences than Pride and Prejudice.
	•	Pride and Prejudice shows tighter sentence distributions, aligning with its sharper dialogue and social wit.
	•	Readability scores suggest subtle differences in syntactic complexity rather than drastic accessibility gaps.
	•	Semantic drift and paragraph-level analysis indicate differences in narrative focus and structural pacing.

Together, these findings suggest that Austen adapts her stylistic choices to suit narrative tone and thematic emphasis, even within her own body of work.

⸻

Requirements

To run the notebooks, install the required Python packages:

pip install -r requirements.txt

Main libraries used:
	•	Python 3.9+
	•	numpy
	•	matplotlib
	•	sentence-transformers
	•	scikit-learn
	•	nltk / regex

⸻

Repository Structure (Suggested)

.
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 1_AppliedNLP_Session3_Sentence_Length.ipynb
│   ├── 2_AppliedNLP_Session3_Readability.ipynb
│   ├── 2_AppliedNLP_Session4_Topic_Drift.ipynb
│   └── 5_AppliedNLP_Session4_Paragraph_Function_Classification.ipynb
└── results/
    └── figures/


⸻

Notes
	•	All analyses are reproducible given the same input texts.
	•	The notebooks are intended to be read in sequence but can also stand alone.
	•	Visualizations produced in the notebooks are used in the accompanying presentation and Medium article.

⸻

License

This project uses public-domain texts and is intended for educational purposes as part of the Applied NLP course.
