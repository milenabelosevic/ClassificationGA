# Classification Grounding Acts German
This is the repository for the paper "LLM-based Classification of Grounding Acts in German" (Accepted at KONVENS 2025)

<pre lang="markdown"> ##  Repository Structure ``` 
  ├── annotation/ # Annotation materials
  │ └── annotation_guidelines.pdf 
  ├── data/ # Datasets 
  │ ├── data/ # Full combined dataset (all domains) │ 
  ├── test_split.csv # In-domain test set
  │ ├── train_split.csv # In-domain training set 
  │ ├── validation_split.csv # In-domain validation set 
  │ └── outofdomain_eval_data.csv # Out-of-domain test set
  ├── results/ # Evaluation results for all models
  ├── scripts/ # Evaluation scripts 
  │ └── evaluate.py # Script to evaluate any trained model
  └── README.md # This file ``` </pre>
