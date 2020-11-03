# Отчет о тестировании  Credit Card Number Validator #
03.11.2020 - 03.11.2020 было проведено установочное тестирование части кода приложения  Credit Card Number Validator.
На тестирование затрачено: 1 час

# описание процесса тестирования #
В процессе тестирования использовались следубщие артефакты:
* Руководство по установке IntelliJ IDEA
* Пример оформления отчетов о тестировании
* Описание ДЗ

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html

Невалидные данные:
Ожидаемым результатом в этой группе данных является ответ консоли Result is FAIL

* 2221008453102677 - отдает ответ OK
* 4716765851448832616 - отдает ответ FAIL
* 5490053428821503 - отдает ответ OK
* 4175003135845514 - отдает ответ FAIL

Валидные данные:
Ожидаемым результатом в этой группе данных является ответ консоли Result is OK

* 5404361923309519 - отдает ответ OK
* 5404360326816757  - отдает ответ OK
* 5404360061161179 - отдает ответ OK
* 5404367069450728 - отдает ответ OK

Тестирование производилось в следующем окружении:
* Windows 10 Pro
* Java 11