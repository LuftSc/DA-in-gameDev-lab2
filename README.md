# DA-in-gameDev-lab2
Отчет по лабораторной работе #2 выполнил(а):
- Бердышев Артём Александрович
- РИ210942
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Познакомиться с программными средствами для организции передачи данных между инструментами google, Python и Unity

## Задание 1
### Реализовать совместную работу и передачу данных в связке Python - Google-Sheets – Unity.
- В облачном сервисе google console подключить API для работы с google sheets и google drive.
![изображение](https://user-images.githubusercontent.com/104849066/194360537-b5cb53cf-4e68-4580-b5a3-4efc1ac35811.png)
- Реализовать запись данных из скрипта на python в google-таблицу. Данные описывают изменение темпа инфляции на протяжении 11 отсчётных периодов, с учётом стоимости игрового объекта в каждый период.
![изображение](https://user-images.githubusercontent.com/104849066/194361151-ea7e1d8f-9b34-4efc-8489-78bbbdb17bc1.png)
![изображение](https://user-images.githubusercontent.com/104849066/194362513-d5f358b7-78ef-42a8-923e-1c72f5c7119a.png)
![изображение](https://user-images.githubusercontent.com/104849066/194362608-89bcdcba-b215-424e-98dd-7ab37d6331b9.png)
- Создать новый проект на Unity, который будет получать данные из google-таблицы, в которую были записаны данные в предыдущем пункте.
![изображение](https://user-images.githubusercontent.com/104849066/194363223-985f1c81-dfa8-4605-b96c-b66781d9c7d7.png)
- Написать функционал на Unity, в котором будет воспризводиться аудио-файл в зависимости от значения данных из таблицы.
![изображение](https://user-images.githubusercontent.com/104849066/194363498-e55ee4f1-8138-4ee1-b1ca-29ef7026d27d.png)
![изображение](https://user-images.githubusercontent.com/104849066/194363603-ad1e25d7-c5bb-450a-b96a-28315cf2f47d.png)
![изображение](https://user-images.githubusercontent.com/104849066/194363675-b83823d9-6937-4a42-973a-2a66a205f9c9.png)
![изображение](https://user-images.githubusercontent.com/104849066/194363994-74696c2c-a1cf-466f-ba70-05736b34dca0.png)

## Задание 2
### Реализовать запись в Google-таблицу набора данных, полученных с помощью линейной регрессии из лабораторной работы № 1. 
- Подключаем необходимые API для работы с google sheets
![изображение](https://user-images.githubusercontent.com/104849066/194364716-1a477a46-4b2e-42e8-9879-87cdfc1bad2a.png)
![изображение](https://user-images.githubusercontent.com/104849066/194365251-9d2f5944-16fd-4757-9704-e612915decd9.png)
- Создаём таблицу в Google Sheets и разрешаем доступ наешму аккаунту
![изображение](https://user-images.githubusercontent.com/104849066/194365804-91a01807-97e8-4d1e-bb53-296ed8cd8426.png)
- Создаём новый скрипт .py и ложим в эту же директорию JSON файл нашего аккаунта
![изображение](https://user-images.githubusercontent.com/104849066/194366425-47a73bd3-88e5-436d-a6da-de26a5e31f2a.png)
- Копируем код линейной регрессии из лабораторной работы номер 1
![изображение](https://user-images.githubusercontent.com/104849066/194366548-31ec4313-226c-4a90-9e21-99f05fe9ceb6.png)
- Импортируем нужные библиотеки и дописываем код,чтобы он заносил данные в Google Sheets
![изображение](https://user-images.githubusercontent.com/104849066/194367994-a86b1fe9-6061-40ef-a449-e51ba4fe4095.png)
- Запускаем код... Готово!
![изображение](https://user-images.githubusercontent.com/104849066/194368298-aba70d36-b692-45ea-93b3-cf5311fb44be.png)
![изображение](https://user-images.githubusercontent.com/104849066/194368413-8def407d-70c9-4419-8393-0287807a4163.png)
## Задание 3
### Самостоятельно разработать сценарий воспроизведения звукового сопровождения в Unity в зависимости от изменения считанных данных в задании 2.
- Создаём новый C# скрипт и навешиваем его на наш пустой GameObject
![изображение](https://user-images.githubusercontent.com/104849066/194374152-509141ed-43c4-4a9d-bf13-5d42b8a40541.png)

