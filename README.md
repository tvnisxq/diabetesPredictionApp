# Pima Indians Diabetes — Diabetes Prediction

A Machine Learning notebook that trains a classifier to predict diabetes from the Pima Indians dataset.

## Contents
- `data/diabetes.csv` — dataset used in the notebook
- `src/diabetes_prediction.ipynb` — main Jupyter notebook with data prep, model training and evaluation

## Requirements
- Python 3.8+ (project includes a virtual environment at `diabetes_venv/`)
- Common libraries: pandas, numpy, scikit-learn, matplotlib, jupyter

## Quick start (Windows, cmd.exe)
1. Activate the virtual environment:

   diabetes_venv\Scripts\activate.bat

2. (Preferred) install dependencies from a requirements file:

   pip install -r requirements.txt

   Or, install common packages directly:

   pip install pandas numpy scikit-learn matplotlib jupyter

3. Launch Jupyter and open the notebook:

   jupyter notebook src/diabetes_prediction.ipynb

4. In the notebook, the dataset is loaded from `data/diabetes.csv`. If you get a FileNotFoundError, ensure the kernel's working directory is the project root or update the path in the notebook (absolute path or use `..` to go up one level if running from `src/`).

## Notes
- The notebook balances classes by downsampling the majority class before training.
- Keep the dataset in `data/` to match the notebook's paths, or update the path in `src/diabetes_prediction.ipynb` to a full absolute path.

## License
This project is licensed under the MIT License — see the `LICENSE` file for details.
