# Отчёт о тестировании KeyValidator

## Краткое описание

7.03.2021 - <Дата окончания> было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1,5 ч

В результате тестирования выявлены следующие дефекты:
* [Валидные ключи не распознаются программой](https://github.com/k-emiko/javaqa1-1/issues/1)
* [Невалидный ключ распознан как валидный](https://github.com/k-emiko/javaqa1-1/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство пользования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные [Руководства пользования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - валидный ключ
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 - валидный ключ Х
* b295bc63-9f03-3b4b-af80-969b39f8c262 - валидный ключ
* 387eedc6-12e9-3b32-9881-63b6b5e85317 - валидный ключ Х
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - валидный ключ
* 18252235-78e0-44a5-8720-556f0c7da17a - невалидный ключ 
* e66075b6-ddad-445e-baf6-161b3289522b - невалидный ключ
* b6d53250-f07e-4352-a293-6102ddf7f1ca - невалидный ключ
* c2bc778a-1cb9-46c6-b435-0489649d2a42 - невалидный ключ
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - невалидный ключ Х

Тестирование производилось в следующем окружении:
* LMDE 4 Debbie, kernel 4.19.0-13-amd64
* openjdk version "11.0.9.1" 2020-11-04
* OpenJDK Runtime Environment (build 11.0.9.1+1-post-Debian-1deb10u2)
* OpenJDK 64-Bit Server VM (build 11.0.9.1+1-post-Debian-1deb10u2, mixed mode, sharing)

