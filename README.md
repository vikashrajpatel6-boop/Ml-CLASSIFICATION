# Iris Flower Classification Using Machine Learning

**Alfido Tech AI/ML Internship — Task 1**

## Project description
This beginner-friendly project trains and compares supervised machine-learning models to predict Iris flower species from sepal length, sepal width, petal length, and petal width. The target classes are Setosa, Versicolor, and Virginica.

## Objectives
- Inspect and check the dataset for missing values and duplicates.
- Explore measurements using plots.
- Split data into training and testing sets.
- Compare Logistic Regression and Decision Tree using five-fold stratified cross-validation.
- Evaluate held-out test predictions with accuracy, macro precision, macro recall, macro F1-score, ROC-AUC, classification reports, and confusion matrices.
- Predict a species for a new sample.

## Technologies
Python 3, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook / Google Colab.

## Dataset
The notebook loads the built-in Iris dataset from Scikit-learn. It has 150 observations, four numeric measurements, and three species classes. No separate dataset download is required.

## Installation
1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. (Optional but recommended) Create and activate a virtual environment.
4. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run the project
Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `iris_classification.ipynb` and run cells from top to bottom. Alternatively, upload the notebook to Google Colab and run all cells.

## Evaluation methods
- Accuracy
- Macro-averaged precision, recall, and F1-score
- Multiclass ROC-AUC using one-vs-rest probabilities and macro averaging
- Classification report and confusion matrix
- Five-fold stratified cross-validation accuracy on the training data

## Results
Run the notebook to generate the actual metric values and plots. Paste the measured results here after execution; do not enter estimated or invented scores.

| Model | Accuracy | Macro Precision | Macro Recall | Macro F1 | ROC-AUC (OvR macro) |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | Fill after running | Fill after running | Fill after running | Fill after running | Fill after running |
| Decision Tree | Fill after running | Fill after running | Fill after running | Fill after running | Fill after running |

## Project folder structure
```text
Iris_Classification/
├── iris_classification.ipynb
├── screenshots/
├── requirements.txt
├── README.md
└── Project_Report.docx
```

- `iris_classification.ipynb`: complete analysis, plots, model training, evaluation, and sample prediction.
- `screenshots/`: add screenshots of important notebook outputs and plots.
- `requirements.txt`: Python libraries needed to run the project.
- `README.md`: project overview and setup instructions.
- `Project_Report.docx`: college/internship report; update placeholders after running the notebook.

## Author
- **Name:** [Your Name]
- **College/University:** [Your College/University]
- **Internship:** Alfido Tech AI/ML Internship
- **Task:** Task 1 — ML Classification Project
- **GitHub:** [Your GitHub Profile URL]
