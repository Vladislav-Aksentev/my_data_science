# Рекомендация тарифов оператора связи.

Задача - анализ данных тарифов оператора связи для рекомендаций клиентам, пользующихся архивными тарифами на основе клиентов, уже перешедших на новые тарифы.

### Общий вывод:

По проведённому подбору моделей, была выбрана RandomForestClassifier. Из гипперпараметров наиболее точными оказались - количество деревьев = 25 с глубиной = 9. Можно сказать, что наша модель точнее чем предсказания дамми и удовлетваряет условиям задания - "Удалось достичь accuracy не меньше 0.75". Осталась проблема в перекосе обучения из-за количественного различия изначальной выборки по тарифам Ультра и Смарт.  

### Статус проекта:

Проект сдан.  

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
