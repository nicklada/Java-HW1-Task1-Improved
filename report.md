# Отчёт о тестировании приложения KeyValidator
## Краткое описание
21.03.2020 - 21.03.2020 было проведено тестирование документации, тестирование установки, интеграционное тестирование приложения KeyValidator. Далее проведено функциональное тестирование с позитивными и негативными сценариями, по результатам которого выявлены ошибки работы приложения. Ошибки оформлены соответственным образом в Issues.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

+ https://github.com/nicklada/Java-HW1-Task1-Improved/issues/1
+ https://github.com/nicklada/Java-HW1-Task1-Improved/issues/2
+ https://github.com/nicklada/Java-HW1-Task1-Improved/issues/3
+ https://github.com/nicklada/Java-HW1-Task1-Improved/issues/4

## Описание процесса тестирования
### Артефакты тестирования:

+ Test Cases: (testcase.md, testcase2.md, testcase3.md)
+ Bug Reports: 
https://github.com/nicklada/Java-HW1-Task1-Improved/issues/1
https://github.com/nicklada/Java-HW1-Task1-Improved/issues/2
https://github.com/nicklada/Java-HW1-Task1-Improved/issues/3
https://github.com/nicklada/Java-HW1-Task1-Improved/issues/4


### В качестве тестовых данных использовались данные Руководства использования (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

+ Для запуска приложения: 
java KeyValidator 00000000-0000-0000-0000-000000000000 00000000-0000-0000-0000-000000000001
Ожидаемый результат: 
Result for 00000000-0000-0000-0000-000000000000: OK
Result for 00000000-0000-0000-0000-000000000001: FAIL

+ Валидные ключи для проверки:
8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
80b427f8-92cd-3aae-ba04-3927fbe17c6
b295bc63-9f03-3b4b-af80-969b39f8c262
387eedc6-12e9-3b32-9881-63b6b5e85317
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Ожидаемый результат: 
Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK


Невалидные ключи:
+ Невалидные ключи для проверки:
18252235-78e0-44a5-8720-556f0c7da17a
e66075b6-ddad-445e-baf6-161b3289522b
b6d53250-f07e-4352-a293-6102ddf7f1ca
c2bc778a-1cb9-46c6-b435-0489649d2a42
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Ожидаемый результат:
Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

## Тестирование производилось в следующем окружении:

+ <версия и разрядность ОС>
+ <версия Java>
+ <другое ПО, при необходимости>