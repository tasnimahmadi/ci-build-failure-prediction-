# Predicting CI Build Failures Before They Run
ML1 capstone project, Tek-Up ING-4-SDIA S7 (2026-2027).

A machine learning model that predicts whether a code change will break the build before the CI pipeline runs it.

## Data
TravisTorrent (Beller, Gousios & Zaidman, MSR 2017), 5 March 2016 snapshot. This is a build-level extract of 14 open-source projects (43,230 builds) and is stored in `data/raw/`.
If the files are missing, the notebook downloads them from a pinned public copy.

## Run
    python -m venv ml_project_env
    source ml_project_env/bin/activate        # Windows: ml_project_env\Scripts\activate
    pip install -r requirements.txt
    jupyter notebook notebooks/CI_Build_Failure_Prediction.ipynb   # Restart Kernel & Run All

## Status
Sections 1-4 (problem, data, EDA, preprocessing) are done. Modelling starts in week 10.
