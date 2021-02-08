# Определения токсичности комментариев(машинное обучение для текстов).  

Подготовка модели для определения токсичности комментариев - машинное обучение для текстов.  

### Общий вывод:

Были предобработаные. Тексты лемматизированы и выброшены стоп слова. Слова превращены в векторы с помощью TF-IDF. Результаты моделей на валидационной выборке:

RandomForestClassifier на выборке с апсемплингом(вместе с даунсемплингом) f1 = 0.37.

ComplementNB = 0.6055159590951349

CatBoostClassifier = 0.7034232050893668

LGBMClassifier = 0.7480474399768585

LogisticRegression = 0.7863202545068929

Исходя из этого, была выбрана логистическая регрессия. Её результаты F1 меры на тестовой выборке = 0.7976969379743521.

Логистическая регрессия - единственная модель из опробованных, результаты которой удовлетворяют условию задания...  

### Статус проекта:

Проект сдан.  

### Инструменты и методы, используемые в реализации:

pandas  

pymystem3.Mystem

re

numpy

nltk
nltk.corpus.stopwords as nltk_stopwords

sklearn.feature_extraction.text.TfidfVectorizer
sklearn.linear_model.LogisticRegression
sklearn.ensemble.RandomForestClassifier
sklearn.naive_bayes.ComplementNB  
sklearn.model_selection.train_test_split  
sklearn.model_selection.GridSearchCV  
sklearn.metrics.f1_score  

lightgbm.LGBMRegressor  

catboost.CatBoostRegressor
