# Sales Prediction Using Python (Data Science Track, Task 5)

Predicts product sales from advertising spend on TV, Radio and Newspaper using Linear Regression (baseline), Polynomial Regression and Random Forest.

## Files
- `sales_prediction.ipynb` - the full, commented notebook
- `data/Advertising.csv` - dataset (the classic "Advertising" data from *An Introduction to Statistical Learning*; budgets in thousand $, sales in thousand units)
- `requirements.txt` - Python dependencies

## How to run
```bash
cd sales-prediction
python -m venv venv
# Windows:   venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
jupyter notebook sales_prediction.ipynb
```
In Jupyter choose **Kernel > Restart Kernel and Run All Cells**.

Keep the `data` folder next to the notebook, because the notebook reads `data/Advertising.csv`.
