# Рекомендация тарифов.

Задача - анализ данных тарифов оператора связи для рекомендаций клиентам, пользующихся архивными тарифами на основе клиентов, уже перешедших на новые тарифы.

### План работ:
1 Ознакомление с данными.
2 Разбиение данных на выборки.
3 Исследование моделей.
4 Проверка модели на тестовой выборке.
5 Проверка модели на адекватность.
6 Общий вывод.

### Библиотеки, используемые в проекте:

pandas,
matplotlib.pyplot,
seaborn,
sklearn.tree.DecisionTreeClassifier,
sklearn.ensemble.RandomForestClassifier,
sklearn.linear_model.LogisticRegression,
sklearn.model_selection.train_test_split,
sklearn.model_selection.GridSearchCV,
sklearn.metrics.accuracy_score,
sklearn.metrics.classification_report,
sklearn.dummy.DummyClassifier
