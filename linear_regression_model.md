# Linear Regression Model

Linear Regression is used to predict a continuous value
by finding a relationship between input features and output.

## Model Equation
y = mx + c

Where:
- y = predicted price
- x = input feature (e.g. house size)
- m = weight
- c = bias

## Conceptual Python Example

```python
from sklearn.linear_model import LinearRegression

# training data (conceptual)
X = [[50], [60], [70]]   # house size
y = [100000, 120000, 140000]

model = LinearRegression()
model.fit(X, y)

prediction = model.predict([[65]])

