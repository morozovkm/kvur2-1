# Проект kvur2

# Система для решения квадратных уравнений

## Для чего нужна система:

* Решение квадратных уравнений
* Решение биквадратных уравнений

## Для кого эта система

* Студенты
* Школьники
    * начальная школа
    * средняя школа

* * *

## Примеры использования

 Для того чтобы запустить приложение выполните `python3 kvtest.py` и введите нужные даннные.

## Как происходит получение данных от пользователя

```python
baddata = True
while baddata:
    try:
        a = int(input('Введите а: '))
        b = int(input('Введите b: '))
        c = int(input('Введите с: '))
        baddata = False
    except ValueError:
        print('Не удалось получить данные!')
```
|Название приложение|Польза приложения|
|-------------------|-----------------|
|kvtest.py|Высокая|

![Kartinka](https://office-guru.ru/wp-content/uploads/2021/08/python-logo.jpeg)

для более успешного использования переходите [мой сайт](http://nadejnei.net "Самый крутой сайт")

## Молодец ли Я?
- [x] Молодец
- [ ] Не молодец

*Курсив*

__Жирный__
