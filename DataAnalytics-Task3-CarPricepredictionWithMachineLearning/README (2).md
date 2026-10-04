# Car Price Prediction (Data Science Track, Task 3)

Predicts the selling price (INR) of a used car from brand, age, mileage, fuel type, seller type, transmission and owner history, using regression models (Linear Regression, Random Forest, Gradient Boosting).

## Files
- `car_price_prediction.ipynb` - the full, commented notebook
- `data/CAR DETAILS FROM CAR DEKHO.csv` - dataset (Kaggle: "Vehicle dataset from CarDekho")
- `requirements.txt` - Python dependencies

## How to run
```bash
cd car-price-prediction
python -m venv venv
# Windows:   venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
jupyter notebook car_price_prediction.ipynb
```
In Jupyter choose **Kernel > Restart Kernel and Run All Cells**.

Keep the `data` folder next to the notebook, because the notebook reads `data/CAR DETAILS FROM CAR DEKHO.csv`.
