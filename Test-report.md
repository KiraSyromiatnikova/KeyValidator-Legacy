# **Отчёт о тестировании KeyValidator** #

## **Краткое описание** ##
19.01.2021 было проведено установочное тестирование, тестирование документации, тестирование совместимости KeyValidator c Java 11, а также функциональное тестирование KeyValidator.

На тестирование затрачено:  1 час

В результате тестирования выявлены следующие дефекты:

* [Валидные ключи 80b427f8-92cd-3aae-ba04-3927fbe17c6 и 387eedc6-12e9-3b32-9881-63b6b5e85317 считываются как невалидные](https://github.com/KiraSyromiatnikova/KeyValidator/issues/1)
* [Невалидный ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 считывается как валидный](https://github.com/KiraSyromiatnikova/KeyValidator/issues/2)

## **Описание процесса тестирования** ##

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* Баг-репорты

В качестве тестовых данных использовались [Ключи для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md).

Тестирование производилось в следующем окружении:
* Windows 10 x64
* Java 11.0.9