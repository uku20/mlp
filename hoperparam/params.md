# Best Parameters

| Model | Parameter | Accuracy | Sampling |
| :--- | :--- | :--- | :--- |
| AdaBoost | {'estimator__max_depth': 10, 'estimator__min_samples_leaf': 5, 'learning_rate': 0.5} | 0.9892665474060823 | Over |
| GradientBoost | {'n_estimators': 300, 'min_samples_leaf': 5, 'max_depth': 10, 'learning_rate': 0.5} | 0.9880739415623137 | Over |
| XGBoost | {'objective': 'multi:logistic', 'num_class': 4, 'n_estimators': 100, 'max_depth': 10, 'learning_rate': 0.1, 'eval_metric': 'merror'} | 0.9747565096402305 | Over |
