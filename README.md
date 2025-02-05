# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Рыжков Анатолий Степанович
- РИ211001

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1
### Написать прогарммы Hello World на Python и Unity.


![image](https://user-images.githubusercontent.com/109138056/192851566-ecd4924b-e609-4bd1-8d4e-ef7aeb052613.png)
![image](https://user-images.githubusercontent.com/109138056/192852481-d7315809-c4cc-451d-9d20-3c009565de49.png)
![image](https://user-images.githubusercontent.com/109138056/192852609-349cbc14-58d7-4250-9a88-625a773cfc1d.png)


## Задание 2
### Пошагово выполнить каждый пункт раздела "ход работы" с описанием и примерами реализации задач.
Ход работы:

1)Произвести подготовку данных для работы с алгоритмом линейной регрессии. 10 видов данных были установлены случайным образом, и данные находились в линейной зависимости. Данные преобразуются в формат массива, чтобы их можно было вычислить напрямую при использовании умножения и сложения.
![image](https://user-images.githubusercontent.com/109138056/192859105-aba61d74-4461-4c8c-a4a7-87ddd7a30a24.png)

2)Определите связанные функции. Функция модели: определяет модель линейной регрессии wx+b. Функция потерь: функция потерь среднеквадратичной ошибки. Функция оптимизации: метод градиентного спуска для нахождения частных производных w и b.
![image](https://user-images.githubusercontent.com/109138056/192860381-fb4f7481-6298-4689-a2e5-c893ef9d0671.png)

3)Начать итерацию
Шаг 1)Инициаизация и модель итеративной оптимизации
![image](https://user-images.githubusercontent.com/109138056/192860482-e48cc8f2-db8f-43e7-a785-721ebbd586a1.png)

Шаг 2)На второй итерации отображаются значения параметров, значаения потерь и эффекты визуализации после итерации
![image](https://user-images.githubusercontent.com/109138056/192860677-2a4392eb-4739-4b8e-9a6b-abb0d50cd908.png)

Шаг 3)Третья итерация показывает значаение параметров, значения потерь и визуализацию после итерации 
![image](https://user-images.githubusercontent.com/109138056/192860948-689e7989-21d1-4592-8f6c-3a3786fa872d.png)

Шаг 4)На четвертой итерации отображаются значения параметров, значения потерь и эффекты визуализации
![image](https://user-images.githubusercontent.com/109138056/192861063-2c9be2ab-8777-498b-a4cd-d077bc788fe1.png)

Шаг 5)Пятая итерация показываент значение параметра, значние потерь и эффект визуализации после итерации
![image](https://user-images.githubusercontent.com/109138056/192861597-beae148e-ecd4-430f-9f14-48d7d0f51a4f.png)

Шаг 6)1000-я итерация, показывающая значения параметров, потери и визуализацию после итерации
![image](https://user-images.githubusercontent.com/109138056/192861671-051cb7f8-ccaa-4233-95eb-b7d2de379e8f.png)

## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
Не должна так как loss показывает величину ошибки, т.е, чем больше она лежит между точками, тем лучше.
![image](https://user-images.githubusercontent.com/109138056/192862613-dd77f187-cef4-4031-bbb8-916fefae89f7.png)
![image](https://user-images.githubusercontent.com/109138056/192862699-dd79fe4e-f564-481e-94c8-f428dcb8d358.png)
![image](https://user-images.githubusercontent.com/109138056/192862804-07e6e034-e969-4824-a0a2-95025584375b.png)
![image](https://user-images.githubusercontent.com/109138056/192862881-2c4ae59a-3577-446d-a9e0-67ead28a043b.png)

### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
Lr- это величина погрешности точек на графике. 
![image](https://user-images.githubusercontent.com/109138056/192863383-a24b8170-0317-4b99-91cd-2ad883bbe583.png)
![image](https://user-images.githubusercontent.com/109138056/192863244-276b1d72-ad00-427f-95fc-d313792e09d8.png)
![image](https://user-images.githubusercontent.com/109138056/192863439-b066050c-38c2-4599-9087-180ae86dcf74.png)
![image](https://user-images.githubusercontent.com/109138056/192863502-f520ce71-4c41-46fc-b244-b0ed6c2f32f2.png)


## Выводы

Я получил опыт в настройке Github, Unity, VScode, узнал базовые функции в языке Python.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
