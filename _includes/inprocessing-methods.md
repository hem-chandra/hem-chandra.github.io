
#### In-processing Methods
In this approach, bias is addressed **during model training**. It often involves modifying the learning algorithm, incorporating fairness constraints or custom loss functions. The dataset is typically divided into training, validation, and testing subsets:
- **Training**: Used to train the model.
- **Validation**: Used for hyperparameter tuning or bias-aware optimization.
- **Testing**: Used for final model evaluation.

{% include_relative _includes/inprocessing-publications.md %}
