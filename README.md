# telecom_churn

Проект заключается в анализе клиентов калифорнийской телекоммуникационной компании за второй квартал 2022 года. За основу было взято испытание от Maven Analytics (https://www.mavenanalytics.io/blog/maven-churn-challenge). В ходе работы будет произведена предобработка данных с помощью pandas, визуализированы с помощью matplotlib, seaborn и plotly. В результате будут даны рекомендации.

Данные:
customer id - уникальный ID клиента
gender - пол клиента, (Male, Female)
age - возраст клиента в годах на конец второго квартала 2022
married - женат ли клиент, (Yes, No)
number of depedents - количество зависимых лиц, живущих с клиентом
city - город
zip code - почтовый индекс
latitude - широта дома
longitude - долгота дома
number of refferals - количество раз, которые клиент приводил друга или родственника
tenure in months - количество месяцев на конец второго квартала, которые клиент с компанией
offer - последние маркетинговое предложение, (Offer A, B, C, D, E, None)
phone service - подписан ли клиент на телефонные сервисы, (Yes, No)
avg monthly long distance charges - средняя стоимость звонков на большое расстояние
multiple lines - использует ли клиент несколько телефонных линий, (Yes, No)
internet sevice - подписан ли клиент на интернет сервис, (Yes, No)
internet type - тип интернета, (DSL, Fiber Optic, Cable)
avg monthly GB download - средний объем загрузки в гигабайтах
online security - подписан ли клиент на дополнительную защиту, (Yes, No)
online backup - подписан ли клиент на восстановление данных, (Yes, No)
device protection plan - подписан ли клиент на план защиты устройств, (Yes, No)
premium tech support - подписан ли клиент на улучшенную техподдержку, (Yes, No)
streaming TV - использует ли клиент интернет для просмотра телевидения со сторонних сервисов, (Yes, No)
streaming movies - для просмотра фильмов со сторонних сервисов, (Yes, No)
streaming music - для прослушивания музыки со сторонних сервисов, (Yes, No)
unlimited data - платит ли клиент за неограниченный объем загрузки, (Yes, No)
contract - тип контракта, (Month-to-Month, One Year, Two Year)
paperless billing - выбрал ли клиент онлайн-оплату, (Yes, No)
payment method - метод оплаты, (Bank Withdrawal, Credit Card, Mailed Check)
monthly charge - месячная оплата
total charges - суммарная оплата
total refunds - суммарные возвраты клиенту
total extra data charges - суммарная оплата за оплату сверх ограничения
total long distance charges - суммарная оплата за звонки на большое расстояние
total revenue - суммарный зароботок компании с клиента
customer status - статус клиента, (Stayed, Churned, Joined)
churn category - категория причины ухода клиента
churn reason - причина ухода клиента
