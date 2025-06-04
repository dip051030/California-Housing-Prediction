# California Housing Prices Analysis

## Description
This project analyzes the California Housing Prices dataset to predict housing prices using a **Random Forest** model. It estimates median house values based on features like location, house age, and income levels, providing insights into housing price trends across California.

---

## Dataset
The dataset (`housing.csv`) contains housing district data with the following features:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Median House Value (target variable)
- Ocean Proximity (categorical)

---

## Project Steps

1. **Load Dataset:** Import data into a Pandas DataFrame.
2. **Explore & Visualize:** Check data structure and visualize relationships using Matplotlib and Seaborn.
3. **Preprocess:** Handle missing values and encode categorical variables.
4. **Split Data:** Divide into training and testing sets.
5. **Train Model:** Fit a Random Forest model on training data.
6. **Evaluate:** Compare actual vs predicted median house values on test samples.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run

1. Make sure Python and Jupyter are installed.
2. Install dependencies:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. Download the `housing.csv` dataset and place it in the project folder.
4. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

5. Open `California Housing Prices.ipynb` and run all cells.

---

## Results

- Full ML pipeline from data loading to model evaluation.
- Key visualization comparing actual vs predicted prices for test samples.
- Insights into California housing price trends.

---

## Acknowledgments

The California Housing dataset is a popular resource for regression tasks in ML.

---

