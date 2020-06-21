# Отчёт о тестировании  KeyValidator

##  Краткое описание

Дата начала 21.06.2020

Дата окончания 21.06.2020 

Было проведено Функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

1.  https://github.com/belolga55/KeyValidator/issues/1
1. https://github.com/belolga55/KeyValidator/issues/2


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

* Баг-репорты
* отчет о тестировании


В качестве тестовых данных использовались данные из Руководства использования https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md :

* Валидные ключи, ожидаемый результат ОК:
1. 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
1. 80b427f8-92cd-3aae-ba04-3927fbe17c6
1. b295bc63-9f03-3b4b-af80-969b39f8c262
1. 387eedc6-12e9-3b32-9881-63b6b5e85317
1. c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

* Невалидные ключи, ожидаемый результат FAIL:
1. 18252235-78e0-44a5-8720-556f0c7da17a
1. e66075b6-ddad-445e-baf6-161b3289522b
1. b6d53250-f07e-4352-a293-6102ddf7f1ca
1. c2bc778a-1cb9-46c6-b435-0489649d2a42
1. 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

**Фактический результат**
* Валидные ключи:
1. Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
1. Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: FAIL
1. Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
1. Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
1. Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK
* Невалидные ключи:
1. Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
1. Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
1. Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
1. Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
1. Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: OK

Тестирование производилось в следующем окружении:

Windows 10 х64

версия Java - "11.0.7" 2020-04-14

