# Отчёт о тестировании Precision

## Краткое описание

17/06/2021 - 17/06/2021 было проведено автоматизированное тестирование приложения Precision.

На тестирование затрачено: 0.5 часа.

В результате тестирования выявлены следующие дефекты:
* [Итоговый бонус считается и выводится не корректно](https://github.com/kotebone/Precision/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [баг-репорт](https://github.com/kotebone/Precision/issues/1)

В качестве тестовых данных использовались данные из условий задания:
* double regularBonus = 0.3;
double specialBonus = 0.6;
ОР: Итоговый бонус считается и выводится корректно

Тестирование производилось в следующем окружении:
* ОС Microsoft Windows [Version 10.0.19042.985]
* Java 11.0.10
* IntelliJ IDEA Community Edition 2021.1.1
