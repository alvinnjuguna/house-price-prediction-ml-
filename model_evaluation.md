
```markdown
# Model Evaluation

After training, a model must be evaluated to understand its performance.

## Common Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared score

Lower error values indicate better predictions.

## Conceptual Example

```python
from sklearn.metrics import mean_squared_error

error = mean_squared_error(actual_prices, predicted_prices)
