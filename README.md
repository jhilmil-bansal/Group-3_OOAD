This repository contains:

- `SRS/` – Software Requirements Specification (IEEE format)
- `PPT/` – OOAD presentation with UML and architecture diagrams
- `model/`
  - `train_model_colab.ipynb` – Google Colab notebook to train the ML model
  - `career_model.joblib` – Trained RandomForest model
  - `model_inference.py` – Script to load model and print top career matches
- `backend/`
  - `app.py` – FastAPI backend exposing `/predict` API
  - `requirements.txt` – Dependencies for the backend

The ML model predicts a suitable career path (Data Analyst, Business Analyst, or Product Analyst) based on skills, CGPA, and projects, as described in the case study and diagrams.
