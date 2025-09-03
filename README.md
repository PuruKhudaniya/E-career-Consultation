# E-career-Consultation

Train a TF-IDF + Logistic Regression classifier to recommend careers based on input skills/profile text.
Files:
- data/ec_profiles.csv (training data)
- train.py (train and save model to src/)
- src/ecareer_model.joblib (created after running train.py)
- app.py (Streamlit demo UI)
- requirements.txt

How to use:
1. Create a venv and install: pip install -r requirements.txt
2. Train: python train.py  # creates src/ecareer_model.joblib
3. Run UI: streamlit run app.py
