# 01. Исследование надёжности заёмщиков 

### Задача

На основе статистики о платёжеспособности клиентов, исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.

### Описание

1. Входные данные (статистика о платёжеспособности клиентов) получены от кредитного отдела банка. 

2. Данные очищены от шума: выбросов, пропусков и дубликатов, а также преобразованы в разные форматы. Заменены типы на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и данные категоризированны.

3. Определена доля платёжеспособных клиентов.

4. Проанализировано влияние семейного положения и количества детей клиента на факт возврата кредита в срок. 

5. Построена модель кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

### Инструменты

`предобработка данных`, `лемматизация`, `pymystem3`, `seaborn`, `matplotlib`, `pandas`
