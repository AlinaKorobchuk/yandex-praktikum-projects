# Защита данных клиентов страховой компании

### Данные
Данные клиентов с информацией о количестве страховых выплат.

**Описание данных**

- Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
- Целевой признак: количество страховых выплат клиенту за последние 5 лет.

### Цель проекта

Защитить данные клиентов страховой компании. Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.



### Выполненные задачи

Подготовка данных, анализ данных, разработка и доказательство алгоритма преобразования, обучение модели линейной регрессии, проверка алгоритма. 

Проект закончен.

### Ключевые выводы:

Теоретически и на практике было выявлено и доказано, что при умножении матрицы признаков на обратимую матрицу качество модели не меняется. Соответственно, в данной задаче умножение матрицы признаков на случайную обратимую матрицу позволит преобразовать признаки таким образом, что по ним невозможно будет восстановить персональную информацию клиентов.

### Используемые библиотеки

Pandas, numpy, sklearn (LinearRegression, train_test_split), seaborn.
