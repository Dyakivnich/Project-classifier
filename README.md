# Прогнозирование окрытия депозита

## Задача проекта

Исследовать [данные](https://github.com/Dyakivnich/DS_job_salaries/blob/master/ds_salaries.csv) банка.

## Знакомство с данными

### Данные о клиентах банка:

age - возраст;  
job - сфера занятости;  
marital - семейное положение;  
education - уровень образования;  
default - имеется ли просроченный кредит;  
housing - имеется ли кредит на жильё;  
loan - имеется ли кредит на личные нужды;  
balance - баланс.

### Данные, связанные с последним контактом в контексте текущей маркетинговой кампании:

contact - тип контакта с клиентом;  
month - месяц, в котором был последний контакт;  
day - день, в который был последний контакт;  
duration - продолжительность контакта в секундах).

### Прочие признаки:

campaign - количество контактов с этим клиентом в течение текущей кампании;  
pdays - количество пропущенных дней с момента последней маркетинговой кампании до контакта в текущей кампании;  
previous - количество контактов до текущей кампании;  
poutcome - результат прошлой маркетинговой кампании.

### Целевая переменная

deposit - согласится ли клиент открыть депозит в банке.

## Результат

Итоговое значение метрики f1-score получилось 0.82.
