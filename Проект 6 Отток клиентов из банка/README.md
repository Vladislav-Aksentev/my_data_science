# Отток клиентов из банка.

Задача - анализ оттока клиентов из банка для выбор стратегии (удержание старых клиентов или привлечение новых клиентов).

### Общий вывод:

Были проанализированы и подготовлены данные «Бета-Банка». Обучены модели без учёта дисбаланса классов. Произведены 3 вида балансировки классов и заново обучены модели. Показатели f1 меры улучшились значительно с 0.54 до 0.64 - слабовато. AUC-ROC сильно не менялся, но ответы модели далеки от случайных на разных вариантах этой самой балансировки. Проведено финальное тестирование, на котором показатель f1 снизился до 0.63.  

### Статус проекта:

Проект сдан.  

### Библиотеки, используемые в проекте:

pandas,  
matplotlib.pyplot,  
seaborn,  
numpy,  
sklearn.tree.DecisionTreeClassifier,  
sklearn.ensemble.RandomForestClassifier,  
sklearn.linear_model.LogisticRegression,  
sklearn.model_selection.train_test_split,  
sklearn.model_selection.GridSearchCV,  
sklearn.metrics.accuracy_score,  
sklearn.metrics.classification_report,  
sklearn.metrics.f1_score,  
sklearn.metrics.roc_auc_score,  
sklearn.preprocessing.OneHotEncoder,  
sklearn.preprocessing.OrdinalEncoder,  
sklearn.preprocessing.StandardScaler,  
sklearn.ensemble.RandomForestClassifier  
