# Отчёт о тестировании модуля

### В модуле реализована функциональность валидации номера банковской карты.

14.06.2021 - 14.06.2021 было проведено функциональное тестирование модуля.

На тестирование затрачено: 1 час.

## В результате тестирования выявлены следующие дефекты:

* [Ошибка валидации карт American Express, MIR, Diners Club - Carte Blanche, Diners Club - International #1](https://github.com/leonidbeltsov/JavaTask1-Credit-Card-Number-Validator/issues/1)
* [Ошибка валидации девятнадцатизначных номеров карт VISA, Discover, JCB #2](https://github.com/leonidbeltsov/JavaTask1-Credit-Card-Number-Validator/issues/2)

### Описание процесса тестирования

В качестве тестовых данных использовались данные:
* [Сайт для генерации и валидации номеров банковских карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [CreditCardGenerator.in](https://creditcardgenerator.in/card-generator/mir)

### Тестирование производилось в следующем окружении:
* Windows 10 Домашняя (x64)  
  Версия  21H1  
  Сборка ОС	19043.1052  
  
* openjdk version "11.0.11" 2021-04-20  
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)  
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
* IntelliJ IDEA 2021.1.2 (Community Edition)  
  
  Build #IC-211.7442.40, built on June 1, 2021  
  Runtime version: 11.0.11+9-b1341.57 amd64
