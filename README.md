# Predicting-Smartphone-Addiction
Baseline Score : 0.96171

## Submissions
01. 0.89551 --> 9.87361
02. 0.89546 (Updated Initial LightGBM Run)


lgb_params = {
    'objective': 'binary',
    'metric': 'auc',
    'learning_rate': 0.05,
    'max_depth': 6,
    'num_leaves': 31,
    'n_estimators': 1000,
    'random_state': 42,
    'n_jobs': -1
}
