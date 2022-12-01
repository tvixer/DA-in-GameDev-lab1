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
В данной лабораторной работе мы в проекте Unity реализуем перцептрон, который умеет производить вычисления: OR, AND, NAND, XOR. Так же построим графики зависимости количества эпох от ошибки обучения.

## Задание 1
### Интегрировать экономическую систему в проект Unity и обучить Ml Agent.

Открыл проект и подключил библиотеки мл агента.
![image](https://user-images.githubusercontent.com/109138056/205101183-06f38b35-bf7b-4136-9c4d-dd68821394df.png)

Обучил нейросеть.
![image](https://user-images.githubusercontent.com/109138056/205101326-7d50e3e7-4837-414c-8d29-3f1d75fedcc6.png)

По завершении обучения файлы сохранились.
![image](https://user-images.githubusercontent.com/109138056/205101744-3b2a19c1-87d4-416a-a48e-098806a40393.png)



## Задание 2
### Опишите результаты, выведенные в TensorBoard.

Ход работы:
На изначальных данных получились такие графики:
![image](https://user-images.githubusercontent.com/109138056/205107463-3b5166e8-e630-499b-bf10-a65742cb575c.png)

Изменил batch_size с 1024 на 2100. Прогнал все пункты заново.
![image](https://user-images.githubusercontent.com/109138056/205108161-ca7570b5-4259-4f75-ac3f-ba55111ca267.png)
График стал всегда равен 1.

Изменил batch_size с 1024 на 300. Прогнал все пункты заново.
![image](https://user-images.githubusercontent.com/109138056/205108306-8fbc5618-f543-4370-96de-2252ae4ecdd3.png)
График стал более кривым.

Вернул batch_size 1024, изменил lambd с 0.95 на 0.9.
![image](https://user-images.githubusercontent.com/109138056/205108537-08ddbe83-6aec-4723-bc3f-b59afcc2b79f.png)
График стал более линеен.

Оставил lambd 0.9 и изменил epsilon с 0.2 на 0.1
![image](https://user-images.githubusercontent.com/109138056/205109541-7403ab45-d2cc-4da4-996f-ec6f4bc313fb.png)
Практически нет изменений.

Изменил num_epoch с 3 на 1
![image](https://user-images.githubusercontent.com/109138056/205109625-f7a6df5a-8edc-4072-9b4f-8956f4c69685.png)
Практически нет изменений.

## Выводы

В данной работе мы внедрили экономическую систему и обучение ML-агента в преокт Unity, познакомились с TensorBoard и файлом конфигурации ML-агента, наглядно увидели как влияют поля конфигурации на обучение агента.

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
