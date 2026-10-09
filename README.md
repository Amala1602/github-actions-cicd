# github-actions-cicd

A small Flask application with a health endpoint and a GitHub Actions workflow
that runs the test suite.

## Run locally

```powershell
python -m pip install -r requirements.txt
python app.py
```

The application listens on `http://127.0.0.1:5000`. Run the tests with:

```powershell
python -m pytest -v
```
