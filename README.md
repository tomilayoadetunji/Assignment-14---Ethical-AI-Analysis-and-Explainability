This project builds a logistic regression model using the UCI Adult Income dataset to predict whether an individual earns more than $50K annually. It demonstrates essential Ethical AI practices by evaluating fairness across gender groups and applying explainability techniques to understand model behavior.

The dataset was preprocessed using one-hot encoding and an 80/20 train-test split, with gender selected as the sensitive attribute. After training, the model was evaluated using accuracy, confusion matrix, and classification metrics. Fairness metrics—including selection rate, false positive rate, and true positive rate—were computed using Fairlearn’s MetricFrame, revealing differences between male and female groups.

To ensure transparency, SHAP was used for global and local feature attributions, and LIME provided interpretable explanations for individual predictions. Both tools highlighted key drivers such as education, marital status, hours worked, and capital gain.

This project demonstrates how fairness analysis and explainability techniques can be integrated into machine learning workflows to create more ethical, transparent, and trustworthy AI models.
