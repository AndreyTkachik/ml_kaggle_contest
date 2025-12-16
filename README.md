Решение для контеста Classification with a Tabular Vector Borne Disease Dataset.

submission_baseline содержит предсказания baseline модели RandomForestClassifier(bootstrap=False, max_depth=30, min_samples_leaf=8, min_samples_split=7, n_estimators=2500).

submission содержит предсказания улучшенной модели RandomForestClassifier(bootstrap=True, max_depth=24, min_samples_leaf=16, min_samples_split=15, n_estimators=5000) с помощью кластеризации признаков (симптомов болезней).
