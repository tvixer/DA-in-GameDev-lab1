# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Рыжков Анатолий Степанович
- РИ211001

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

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
![Снимок экрана (25)](https://user-images.githubusercontent.com/114180894/192604408-37438159-4541-456d-ba0e-b2c8df8fcec3.png)

2)Определите связанные функции. Функция модели: определяет модель линейной регрессии wx+b. Функция потерь: функция потерь среднеквадратичной ошибки. Функция оптимизации: метод градиентного спуска для нахождения частных производных w и b.
![Снимок экрана (26)](https://user-images.githubusercontent.com/114180894/192604529-bc5de1e2-0a67-46e6-82f0-bf23a1c3ef21.png)

3)Начать итерацию
Шаг 1)Инициаизация и модель итеративной оптимизации
![Снимок экрана (27)](https://user-images.githubusercontent.com/114180894/192604706-b7fa5b1a-ec1d-4d8a-8590-736779b75e4d.png)

Шаг 2)На второй итерации отображаются значения параметров, значаения потерь и эффекты визуализации после итерации
![Снимок экрана (27)](https://user-images.githubusercontent.com/114180894/192604892-63c8fe75-c880-42b2-8122-8790205cd6d6.png)

Шаг 3)Третья итерация показывает значаение параметров, значения потерь и визуализацию после итерации 
![Снимок экрана (28)](https://user-images.githubusercontent.com/114180894/192605132-de4a81cc-2b8c-471d-af0d-a7a99537d0d0.png)

Шаг 4)На четвертой итерации отображаются значения параметров, значения потерь и эффекты визуализации
![Снимок экрана (28)](https://user-images.githubusercontent.com/114180894/192605296-ea4cd53f-f631-4e5a-94b6-65b1d4651758.png)

Шаг 5)Пятая итерация показываент значение параметра, значние потерь и эффект визуализации после итерации
![Снимок экрана (29)](https://user-images.githubusercontent.com/114180894/192605438-2a78280c-0320-4b1f-9c29-952bcf79359d.png)

Шаг 6)1000-я итерация, показывающая значения параметров, потери и визуализацию после итерации
![Снимок экрана (29)](https://user-images.githubusercontent.com/114180894/192605650-146195c7-b45c-4b13-b1de-cbdf8fa9e25f.png)

## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
Не должна так как loss показывает величину ошибки, т.е, чем больше она лежит между точками, тем лучше.
![Снимок экрана (30)](https://user-images.githubusercontent.com/114180894/192610036-0f343fb2-988c-4cd9-9a00-1e2f73f95456.png)
![Снимок экрана (31)](https://user-images.githubusercontent.com/114180894/192610039-3cbf491e-cb5f-4ed4-af33-22f83f532e55.png)
![Снимок экрана (32)](https://user-images.githubusercontent.com/114180894/192610042-dd274899-f9fc-4ae5-8dd1-07bdcefd2b54.png)
![Снимок экрана (33)](https://user-images.githubusercontent.com/114180894/192610045-40074b88-b424-4fc8-bc56-bac05367f8c9.png)

### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
Lr- это величина погрешности точек на графике. 
![Снимок экрана (37)](https://user-images.githubusercontent.com/114180894/192610494-41aae35e-4e14-4e69-8535-d424be0f2caa.png)
![Снимок экрана (34)](https://user-images.githubusercontent.com/114180894/192610499-608f925c-6d75-4262-8575-cdea17d7ce1c.png)
![Снимок экрана (35)](https://user-images.githubusercontent.com/114180894/192610503-6d19e903-ae7e-487e-84b3-eb27e06cef89.png)
![Снимок экрана (36)](https://user-images.githubusercontent.com/114180894/192610504-4fb06c61-2e7a-4687-84c6-fe5d419607e2.png)


## Выводы

Я ознакомился с основными операторами языка Python на примере реализации линейной регрессии. В Python изучил новые библиотки. А также методы вычисления  предсказания и методы уменьшения этих потерь. Улучшились знания и понимание работы в Unity. А также научился интегрировать эту платформу с VS Code. Научился производить подготовку данных для работы алгоритмом линейной регрессии, определять связанные функции. Также наглядно изучился возможные итерации и увидел изменение параметров и их влияние на график 

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
