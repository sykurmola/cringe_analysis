# Проекты по анализу данных
## Сертификат: https://drive.google.com/file/d/1aBvx4LefKv0suLkFSzHJSaEdaw56RJTH/view?usp=sharing

Это репозиторий для проектов, которые я выполняла в рамках прохождения курса "Анализ данных" от Яндекс.Практикума. Более детальное описание контекста, задач, данных и инструментов содержится в README-файле в папке с проектом. 

| Название проекта      | Описание проекта | Стек технологий проекта     |
| :---                  | :---             | :---         |
| [Создание дашборда по пользовательским событиям для агрегатора новостей](https://github.com/sykurmola/cringe_analysis/blob/main/automatization/zen.ipynb)      |В юпитере создана коннекция к БД, сформирован sql-запрос, в csv-файл выгружены данные о действиях пользователей Яндекс.Дзена, затем по ним построен дашборд с метриками взаимодействия пользователей с карточками статей.  | python, sqlalchemy, postgresql, tableau |
| [Проверка гипотез по увеличению выручки интернет-магазина и оценка результатов A/B-теста](https://github.com/sykurmola/cringe_analysis/blob/main/ab%20tests/hypotheses%20testing.ipynb)| С помощью фреймворков ICE и RICE приоритизированы гипотезы по увеличению выручки интернет-магазина. Проведён анализ результатов A/B-теста: проверена корректность проведения теста, построены графики кумулятивной выручки, среднего чека и конверсии по группам, проверены гипотезы о наличии статистически значимых различий в конверсии и среднем чеке между группами (до и после удаления аномальных пользовтелей). Сделан вывод о нецелесообразности продолжения теста. | python, pandas, matplotlib, scipy |
| [Выявление профилей потребления покупателей интернет-магазина](https://github.com/sykurmola/cringe_analysis/tree/main/e-com%20project)   | На основе данных о транзакциях интернет-магазина товаров для дома и быта выполнена сегментация покупателей по профилю потребления, для этого проведена категоризация товаров. В отдельную группу выделены оптовые клиенты, выявлены особенности их поведения. Определены наиболее популярные категории товаров. Проверены гипотезы: средний чек у тех, кто чаще всего покупает товары категории "растения и семена", ниже, чем у тех, кто покупает товары категории "хранение и порядок"; средний чек в заказах, сделанных в будние дни, ниже, чем в заказах, сделанных в выходные.  | pandas, matplotlib, numpy, scipy |
|[Прогнозирование вероятности оттока пользователей для фитнес-центра](https://github.com/sykurmola/cringe_analysis/blob/main/ml%20basics/churn%20predicting.ipynb)| Для каждого клиента фитнес-центра с помощью машинного обучения спрогнозирована вероятность оттока в следующем месяце. Проанализированы факторы, влияющие на отток. Выполнена кластеризация клиентов с помощью модели, обученной на основании алгоритма K-Means | pandas, scikit-learn, seaborn |
| [Исследование данных Яндекс.Музыки - сравнение пользователей двух городов](https://github.com/sykurmola/cringe_analysis/blob/main/python%20basics/python%20basics.ipynb) | На основе данных Яндекс.Музыки сравнивается поведение пользовтелей из Москвы и Санкт-Петербурга | python, pandas |
| [Исследование надёжности заёмщиков - анализ банковских данных](https://github.com/sykurmola/cringe_analysis/blob/main/data%20preprocessing/credit%20scoring.ipynb) |  На основе данных кредитного отдела банка определено, как разные факторы влияют на возврат кредита в срок (возраст, семейное положение, уровень дохода, цель кредита). Проведена категоризация дохода и целей кредита | python, pandas |
|[Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости](https://github.com/sykurmola/cringe_analysis/blob/main/eda/real%20estate%20market%20eda.ipynb)|На основе данных сервиса Яндекс.Недвижимость установлены параметры для определения рыночной стоимости объектов недвижимости. В таблицу добавлено несколько новых параметров. Изучены факторы, влияющие на стоимость квартиры. Определено 10 населённых пунктов с наибольшим числом объявлений и средняя цена квадратного метра в каждом из них. Выделен и проанализирован сегмент квартир в центре Санкт-Петербурга.|pyhon, pandas, matplotlib|
|[Определение выгодного тарифа для телеком-компании](https://github.com/sykurmola/cringe_analysis/blob/main/statistical%20analysis/telecom%20tariffs.ipynb)| На основе данных клиентов оператора сотовой связи выбран наиболее выгодный для компании тариф. Произведены необходимые дополнительные расчёты, проанализировано поведение клиентов на основе выборки. Проверены гипотезы о различии выручки: абонентов тарифов "ультра" и "смарт"; абонентов из Москвы и из других городов. | pandas, matplotlib, scipy, numpy|
|[Изучение закономерностей, определяющих успешность игр](https://github.com/sykurmola/cringe_analysis/blob/main/first%20module%20project/gamedev.ipynb)|Определены параметры, влияющие на успешность игры в разных регионах. Выделены потенциально прибыльные платформы. Составлен портрет пользователя из каждого региона. Проврены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.| python, pandas, matplotlib, numpy |
|[Анализ убытков приложения ProcrastinatePRO+](https://github.com/sykurmola/cringe_analysis/blob/main/bi/entertainment%20app%20losses.ipynb)| Проведён когортный анализ (LTV, CAC, retention rate). Проанализирована окупаемость рекламы (с разбивокй по устройствам, странам, рекламным каналам). Выявлен неэффективный канал привлечения и другие факторы, мешающие привлечению | python, pandas, matplotlib |
|[Исследование рынка заведений общственного питания Москвы](https://github.com/sykurmola/cringe_analysis/blob/main/data%20visualization/msc%20catering.ipynb) | На основе данных о заведениях общественного питания в Москве сделана попытка оценить перспективы открытия нового кафе. Определено соотношение разных видов объектов, сетевых и несетвых заведений, определены характеристики типичного сетевого заведения. Определены улицы с наибольшим и наименьшим количеством объектов общественного питания, а также с привлечением стороннего датасета определено, в каких районах расположены эти улицы. На основе исследования подготовлена презентация для заказчика. | python, seaborn, plotly |
|[Исследование поведения пользователей сервиса для покупки продуктов](https://github.com/sykurmola/cringe_analysis/blob/main/second%20module%20project/in-app%20behavior.ipynb) | Основной целью этого проекта было изучение принципов событийной аналитики. Построена воронка продаж, определено, на каком этапе теряется больше всего пользователей. Проанализированы результаты теста: с помощью сравнения контрольных групп проверена корректность разделения трафика, затем сравнением с экспериментальной группой проверена гипотеза о том, что изменение шрифта повлияет на поведение пользователей.| matplotlib, seaborn, plotly |
