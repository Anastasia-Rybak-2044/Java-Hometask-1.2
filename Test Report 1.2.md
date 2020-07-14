# Отчет о тестировании Credit Card Number Validator

## Краткое описание
14/07/2020 – 14/07/2020 было проведено функциональное тестирование приложения «Credit Card Number Validator».

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

* Не валидируются номера карты с числом символов, не равным 16
https://github.com/Anastasia-Rybak-2044/Java-Hometask-1.2/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Руководство по установке IntellijIdea
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md
*Java код, ссылка: 
https://github.com/netology-code/javaqa-homeworks/tree/master/intro 


В качестве тестовых данных использовались данные с ресурса:
https://www.freeformatter.com/credit-card-number-generator-validator.html 
и с ресурса:
https://www.vccgenerator.com/

VISA:
* 4485601767089411 (16)
* 4485328547378191 (16)
* 4539230862856906605 (19)

MasterCard:
* 5188283861695422 (16)
* 5487045300128937 (16)
* 5526423433743604 (16)

Diners Club - Carte Blanche:
* 30313262009161 (14) 
* 30212425614315 (14)
* 30024126272727 (14)

American Express (AMEX):
* 345680471397524 (15)
* 343751774427326 (15)
* 376705499331205 (15)

Maestro
* 677128967515 (12)
* 676280231397 (12)
* 6390022006947474805 (19)

## Тестирование производилось в следующем окружении:

* Ноутбук: HP-Pavilion-Gaming-Laptop-15
* ОС: Linux Mint 19.3 x 64
* Версия Java: openjdk 11.0.7 2020-04-14
* Браузер: Google Chrome
