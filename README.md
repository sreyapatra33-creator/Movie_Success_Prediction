# IMDb Movie Rating Predictor

This Streamlit app predicts an IMDb rating category using the model and preprocessing artifacts produced by `model_training.ipynb`.

## Run locally

From this folder, create and activate a virtual environment, install the dependencies, then run:

```powershell
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

The app opens at `http://localhost:8501`.

## Deploy with Streamlit Community Cloud

1. Create a GitHub repository containing `app.py`, `requirements.txt`, and the complete `models/` folder.
2. Push the repository to GitHub. Do not include the raw training data or notebooks unless you want to publish them.
3. In Streamlit Community Cloud, select **Create app**, choose the repository and branch, and set the main file path to `app.py`.
4. Deploy. The app loads its artifacts relative to `app.py`, so no path changes are needed in the cloud.

The `models/` folder is required at runtime. If GitHub rejects a large model file, use Git LFS or host the artifact in a supported private storage location and add a secure download step.
