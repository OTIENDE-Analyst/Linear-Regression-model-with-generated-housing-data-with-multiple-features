# Linear-Regression-project-with-generated-housing-data-with-multiple-features
This project demonstrates a Linear Regression machine learning project built using Python in a Jupyter Notebook.

Synthetic data was generated using Numpy to simulate real world housing price factors. This model predicts house prices based on the Size of the house, number of bedrooms and number of bathrooms.

## What the project covers
- Data generation using Numpy.
- Linear Regression concepts.
- Machine learning workflow.
- Model trainig and prediction.
- Model evaluation

## Dataset generation
The dataset was generated using random values with Numpy.

Random.seed(42) was used to ensure that everytime the code runs we get the same random values. 

The number of samples (n_samples) generated was set to 100.

The Features(X) generated (Dependent variables)include:
1. size - Size of the house.
2. bedrooms - Number of bedrooms in the house
3. bathrooms - Number of bathrooms

The Target variable(y) - Independent variable: 
- price
The  pricing formula used is:
price(y) = B1 *size + B2 * bedrooms + B3 * bathroom + B0
where:
- B1, B2 and B3 are the coefficients
- B0 is the intercept
- price - output(dependent variable)
- size, bedrooms and bathrooms - the features
```
price = 200 * size + 50000 * bedrooms + 10000 * bathrooms + np.random.normal(0, 50000, n_samples)
```
  
## Tools and Technologies used
1. Python
2. Jupyter Notebook
3. Numpy
4. Pandas
5. Matplotlib
6. Scikit-learn
7. Seaborn

## Project workflow
1. Generation of the data with Numpy.
2. Processing the data to ensure the data is clean and also visualized it.
3. Separate the features(X) and labels (y). Then split the data into training data(80%) and test data(20%).
4. Choose an algorithm/model to use. Applied LinearRegression using Scikit-learn..
5. Train the model.
6. Make predictions on the test data.
7. Model evaluation using Mean squared error(mse), r2_score and rmse.

# How to run the project
1. Clone the repository:
```bash
git clone
https://github.com/OTIENDE-Analyst/Linear-Regression-model-with-generated-housing-data-with-multiple-features
```

2. Open Jupyter Notebook:
```bash
jupyter notebook
```



