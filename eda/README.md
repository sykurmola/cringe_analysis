**Статус проекта:** закончен

**Описание данных:** данные сервиса Яндекс Недвижимость, архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

**Задача:** установить параметры для определения рыночной стоимости объектов недвижимости.

**Результат** 

В таблицу добавлены характеристики: 

- цена квадратного метра;
- день недели, месяц и год публикации объявления;
- этаж квартиры; варианты — первый, последний, другой;
- соотношение жилой и общей площади, а также отношение площади кухни к общей.

Уставновлено, сколько по времени обычно занимает продажа, удалены аномальные значения. Изучены факторы, влияющие на стоимость квартиры: больше всего на стоимость влияют площадь и расстояние до центра. Определено 10 населённых пунктов с наибольшим числом объявлений и средняя цена квадратного метра в каждом из них. Также выделен и проанализирован сегмент квартир в центре Санкт-Петербурга.

**Инструменты:** pyhon, pandas, matplotlib
