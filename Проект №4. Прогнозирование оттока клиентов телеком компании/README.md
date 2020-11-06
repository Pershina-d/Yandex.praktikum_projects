# Прогнозирование оттока клиентов телеком компании.

### Тех. стек:
Pandas, Numpy, Datetime, Matplotlib, Seaborn, Scipy (Stats), Scikit-learn (Train_test_split, GridSearchCV, DummyClassifier, StandardScaler, Accuracy_score, Roc_auc_score, ), LightGBM (LGBMClassifier), XGboost (XGBClassifier)

### В процессе выполнения:

- была проведена предобработка данных;
- выполнен анализ данных: выделен актуальный период, целевой признак, оценена значимость влияния факторов на целевой признак, выявлена проблема дисбаланса класса, проведена проверка на мультиколлениарность (высокой зависимости двух признаков друг от друга);
- на основании метрик качества ROC_AUC и Accuracy на тестовой выборке была выбрана наилучшая модель.
