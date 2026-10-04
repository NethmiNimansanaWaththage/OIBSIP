# Iris Flower Classification (Data Science Track, Task 1)

Classifies iris flowers (Setosa, Versicolor, Virginica) from their measurements using scikit-learn.

## Files
- `iris_classification.ipynb` - the full, commented notebook (EDA, plots, 4 classifiers, evaluation, best model)
- `requirements.txt` - Python dependencies

## How to run
```bash
cd iris-classification
python -m venv venv
# Windows:  venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
jupyter notebook iris_classification.ipynb
```
In Jupyter choose **Kernel > Restart & Run All**.

No dataset download is needed; it loads from `sklearn.datasets.load_iris()`.
