# Исследование оттока клиентов

### Данные
Информация о договорах клиентов, пресональных данных, об интернет-услугах и об услугах телефонии для каждого клиента.

### Описание данных:

- contract.csv — информация о договоре;
- personal.csv — персональные данные клиента;
- internet.csv — информация об интернет-услугах;
- phone.csv — информация об услугах телефонии.

### Цель проекта
Построить модель, прогнозирующую отток клиентов.

### Выполненные задачи

Подготовка данных, создание дополнительных признаков, кодирование признаков, анализ данных, визуализация, борьба с дисбалансом, подбор параметров для моделей предсказания, обучение нескольких моделей, проверка на тестовой выборке.

Проект закончен.

### Ключевые выводы:

Наименьшее значение метрики RocAUC у модели градиентного бустинга, обученнjq на данных без урегулирования дисбаланса. Поэтому данная модель предлагается для предсказания оттока клиентов.

### Используемые библиотеки

Pandas, lightgbm, sklearn (LinearRegression, RandomForestRegressor, GridSearchCV, StandardScaler, train_test_split, roc_curve, OneHotEncoder), phik, matplotlib, seaborn, datetime, imblearn, .
