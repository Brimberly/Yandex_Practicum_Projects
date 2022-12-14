# Приоритизация гипотез и анализ результатов А/В-теста

## Задача

Используя данные интернет-магазина, приоритезировать гипотезы, произвести оценку результатов A/B-тестирования.

## Выводы

1. Была проведена приоритизация гипотез с помощью фреймворков ICE и RICE, в результате, с учетом всех факторов, выявлены две наиболее подходящие для тестирования гипотезы.

2. При проверке групп тестирования были выявлены пользователи, попавшие в обе группы. Данные о таких пользователях были удалены из обеих групп.
  
3. По результатам проведенного тестирования группа В показала лучшие результаты, несмотря на снижение среднего чека при тесте "очищенных" данных — высокая конверсия группы перекрывает этот недостаток. Тест признаем успешным и фиксируем победу группы В.

## Используемые библиотеки
*pandas*

*scipy*

*numpy*

*matplotlib*

## Статус проекта
Завершен
