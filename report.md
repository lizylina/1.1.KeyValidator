# Отчёт о тестировании KeyValidator

## Краткое описание

12.06.2020 г. было проведено позитивное и негативное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* https://github.com/lizylina/1.1.KeyValidator/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* инструкция по установке OpenJDK 11;
* руководство использования;
* баг-репорты;
* данный отчет о тестировании.

В качестве тестовых данных использовались ключи для проверки из Руководства использования KeyValidator:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998, ожидаемый результат - OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6, ожидаемый результат - OK
* b295bc63-9f03-3b4b-af80-969b39f8c262, ожидаемый результат - OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317, ожидаемый результат - OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180, ожидаемый результат - OK
* 18252235-78e0-44a5-8720-556f0c7da17a, ожидаемый результат - FAIL
* e66075b6-ddad-445e-baf6-161b3289522b, ожидаемый результат - FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca, ожидаемый результат - FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42, ожидаемый результат - FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1, ожидаемый результат - FAIL

Тестирование производилось в следующем окружении:
* Версия и разрядность ОС: Windows10 x64
* Версия Java: openjdk version 11.0.7
