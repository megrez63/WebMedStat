# WEBmedSTAT. Визуализация медицинской статистики

**Цель** проекта – создание дашборда, отображающего динамику статистических данных за 23 года.

**Тема** дашборда - демографическая ситуация в России.

**Данные** получены путем парсинга сайта Росстата - оцифрованных аналитических сборников "Здравоохранение в России" за период с 2001 по 2023 годы. Данные являются общедоступными, их использование в любых коммерческих и некоммерческих проектах разрешено. Исходные данные были дополнены самостоятельной выгрузкой информации о численности населения по регионам и возрастным группам по субъектам РФ с портала showdata.gks.ru.

Исследуемые **гипотезы**: подтверждаются ли предположения о том, что за период 2001 - 2023:
- общая численность населения страны снижается;
- население в своей массе становится более старым;
- население умирает в более молодом возрасте;
- женщины рожают в более старшем возрасте;
 - соотношение мертворожденных мужского и женского пола не имеет статистически значимых отличий, в то время как соотношение перинатально умерших (первые 168 часов, 7 суток после родов) мальчиков и девочек всегда (из года в год) выше у мальчиков.

1. **[Тетрадь](https://github.com/megrez63/WebMedStat/blob/main/RosStats.ipynb)**
   - предобработка исходных данных для формирования дашборда;
   - статистическая проверка гипотез;
   - библиотеки: *pandas, numpy, matplotlib, statsmodels*.
2. **[Дашборд](https://datalens.yandex/oa9gdxk4re3gc)**
