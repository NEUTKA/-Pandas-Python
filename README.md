# Минипроект 2: Продвинутый pandas и визуализация данных

## О проекте
Во втором минипроекте я продолжил работу с pandas и познакомился с основами визуализации данных на Python. Мне предстояло проанализировать и визуализировать данные о клиентах и их активности.

## Задачи
1. **Импорт данных**
   - Импортируйте библиотеку pandas как `pd`.
   - Загрузите два датасета `user_data` и `logs`.
   - Проверьте размер таблицы, типы переменных, наличие пропущенных значений и выведите описательную статистику.

2. **Анализ данных**
   - Определить, какой клиент совершил наибольшее количество успешных операций (`success == True`).
   - Выяснить, с какой платформы осуществляется наибольшее количество успешных операций.
   - Определить, какую платформу предпочитают премиумные клиенты.
   - Визуализировать распределение возраста клиентов в зависимости от типа клиента (премиум или нет).
   - Постройть график распределения числа успешных операций.
   - Постройть график числа успешных операций, совершенных на платформе `computer`, в зависимости от возраста, используя `sns.countplot` (ось `x` — возраст, ось `y` — число успешных операций). Определить, клиенты какого возраста совершили наибольшее количество успешных операций.

## Описание данных
### Датасет `user_data`
- **client** – идентификатор пользователя
- **premium** – является ли клиент премиум
- **age** – возраст клиента

### Датасет `logs`
- **client** – идентификатор пользователя
- **success** – результат операции (успех – 1, неуспех – 0)
- **platform** – платформа, с которой была совершена операция
- **time** – время в формате Unix

# MiniProject 2: Advanced Pandas and Data Visualization

## About the Project
In this second mini-project, I continued working with pandas and explored the basics of data visualization in Python. My task was to analyze and visualize data on clients and their activity.

## Tasks
1. **Data Import**
   - Import the pandas library as `pd`.
   - Load two datasets, `user_data` and `logs`.
   - Check the table dimensions, variable types, check for any missing values, and display descriptive statistics.

2. **Data Analysis**
   - Determine which client completed the highest number of successful operations (`success == True`).
   - Identify the platform with the highest number of successful operations.
   - Determine the platform preferred by premium clients.
   - Visualize the age distribution of clients based on client type (premium or not).
   - Plot the distribution of the number of successful operations.
   - Create a plot of the number of successful operations made on the `computer` platform by age, using `sns.countplot` (`x-axis` – age, `y-axis` – number of successful operations). Identify the age group with the highest number of successful operations.

## Data Description
### `user_data` Dataset
- **client** – unique identifier for each user
- **premium** – indicates whether the client is premium
- **age** – age of the client

### `logs` Dataset
- **client** – unique identifier for each user
- **success** – operation result (1 for success, 0 for failure)
- **platform** – platform from which the operation was made
- **time** – timestamp in Unix format
