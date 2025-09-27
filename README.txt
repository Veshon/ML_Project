
ITS2130 - Clinical Document Classification (Project)
===================================================

Files included:
- notebooks/1_eda_and_preprocessing.ipynb
- notebooks/2_classification_modeling.ipynb
- notebooks/3_clustering_analysis.ipynb
- artifacts/ (created by notebooks when run)
- requirements.txt

How to run:
1. Create a fresh virtual environment and install dependencies from requirements.txt.
2. Open the notebooks in JupyterLab/Notebook.
3. Run 1_eda_and_preprocessing.ipynb first to fit and save the TF-IDF vectorizer.
4. Then run 2_classification_modeling.ipynb to train the classifier and save artifacts/model_pipeline.joblib.
5. Run 3_clustering_analysis.ipynb for clustering work.

Notes:
- Notebooks download the dataset from Hugging Face. Internet access is required.
- For Vertex AI deployment (Part 4), you'll need a GCP project, billing enabled, and Vertex AI permissions. The notebooks include comments where to add GCS upload and Vertex CLI/API steps.
