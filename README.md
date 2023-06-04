<h2 align="left">В этом репозитории собраны проекты, выполненные в рамках обучения <br />
<h3 align="left">Проекты  представляют собой тетради Jupyter Notebook </h3>

| Название проекта      |Сферы деятельности |Задачи проекта   |Описание проекта      |Инструменты    |
| -------------         |---------------    |-------------    | -------------        | -------------          |     
| [Поиск инсайтов для развития приложения "Ненужные вещи" ](https://github.com/angolechka/portfolio/blob/881f47772caaf404668757d5b92d8ae1e720b50b/%D0%92%D1%8B%D0%BF%D1%83%D1%81%D0%BA%D0%BD%D0%BE%D0%B8%CC%86%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82.ipynb)|`Интернет-сервисы`, `Интернет-магазины`, `Площадки объявлений`|На основе всех полученных данных в курсе выполнить буткемп-проект в сфере e-commerce| Приложение "Ненужные вещи" уже достаточно популярное. Цель исследования - найти интересные инсайты, которые помогут сделать приложене еще лучше. Результаты анализа и рекомендации по улучшению продукта представлены продакт-менеджеру. |`python`, `pandas`, `numpy`, `matplotlib`, `plotly`, `seaborn`, `scipy`, `cufflinks`|
| [Создание дашборда по пользовательским событиям для агрегатора новостей](https://github.com/angolechka/portfolio/blob/a1897838035ec4848b0dbd9bf5afb9c1fed8d5ad/%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.ipynb)|`Интернет-сервисы`, `Площадки объявлений`|Используя данные Яндекс.Дзена построить дашборд с метриками взаимодействия пользователей с карточками статей|Работу над этим проектом я провела на удаленной машине в сервисе Yandex.Cloud. Мной был установлен PostgreSQL, развернута база данных. Затем я написала скрипт пайплайна, который позволил собирать данные за определенный временной период и настроила его автономную работу через crontab. Для визуализации собранных данных я написала скрипт дашборда с несколькими фильтрами и также запустила его на удаленной машине. По результатам была подготовлена презентация с полученными графиками|`python`, `pandas`, `sqlalchemy`, `postgresql`, `dash`, `tableau`|
| [Анализ пользовательского поведения в мобильном приложении](https://github.com/angolechka/portfolio/blob/09cbb6e51bd19b7306e2ad68641f9b43d98184ec/%D0%A1%D0%B1%D0%BE%D1%80%D0%BD%D1%8B%D0%B8%CC%86%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82_2.ipynb)|`Стартапы`, `Бизнес`, `Интернет-сервисы`|На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования|В данном проекте мной были изучены принципы событийной аналитики. Я построила воронку продаж, исследовала путь пользователей до покупки. Проанализировала результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой. Выявлено, что новый шрифт значительно не влияет на поведение пользователей. |`python`, `pandas`, `numpy`, `matplotlib`, `scipy`, `seaborn`, `datetime`|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](https://github.com/angolechka/portfolio/blob/d27143fa11532938081e4cb1f0cb155e516fcebe/%D0%9A%D0%B0%D0%BA%20%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C%20%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8E%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-2.ipynb)|`Стартапы`, `Бизнес`, `Оффлайн`|Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов |Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовала библиотеки seaborn, plotly, cufflinks. |`python`, `pandas`, `plotly`, `seaborn`, `re`, `folium`, `geojson`, `cufflinks`|
| [Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста](https://github.com/angolechka/portfolio/blob/ed3966ea64414b432706f86d7c62cb25e03521b6/A-B%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.ipynb)|`Интернет-магазины`|Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами|Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провела анализ результатов A/B-теста, построила графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитала статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. |`python`, `pandas`, `numpy`, `matplotlib`, `plotly`, `seaborn`, `scipy`, `cufflinks`|
| [Анализ убытков приложения ProcrastinatePRO+](https://github.com/angolechka/portfolio/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B5%D1%8D%D1%84%D1%84%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BF%D1%80%D0%B8%D0%B2%D0%BB%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20Procrastinate%20Pro%2B.ipynb)|`Интернет-сервисы`,`Стартапы`|Основная цель исследования — разобраться в причинах неэффективности привлечения пользователей приложения и дать рекомендации для отдела маркетинга, чтобы компания могла выйти в плюс. |Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.|`python`, `pandas`, `matplotlib`, `seaborn`|
| [Исследование рынка компьютерных игр](https://github.com/angolechka/portfolio/blob/main/%D0%A1%D0%B1%D0%BE%D1%80%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%20%D0%B8%D0%B3%D1%80%D1%8B.ipynb)|`Gamedev`, `Интернет-сервисы`|Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры |Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовала критерий Стьюдента для независимых выборок.|`python`, `pandas`, `numpy`, `matplotlib`, `scipy`|
| [Определение перспективного тарифа для телеком компании](https://github.com/angolechka/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.ipynb)|`Телеком`|На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа|Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. |`python`, `pandas`, `numpy`, `matplotlib`, `scipy`|
| [Аналииз рынка недвижмости - продажа квартир в Яндекс.Недвижимость](https://github.com/angolechka/portfolio/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80.ipynb) |`Интернет-сервисы`, `Площадки объявлений`| Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир|На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.|`python`, `pandas`, `matplotlib` |
| [Исследование надёжности заёмщиков — анализ банковских данных](https://github.com/angolechka/portfolio/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%B7%D0%B0%D0%B5%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2.ipynb)|`Банковская сфера`, `Кредитование`| На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок|На основе данных кредитного отдела банка исследовала влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.|`python`, `pandas`|   
| [Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](https://github.com/angolechka/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%9C%D1%83%D0%B7%D1%8B%D0%BA%D0%B0%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D1%85%20%D0%B3%D0%BE%D1%80%D0%BE%D0%B4%D0%BE%D0%B2.ipynb)|`Интернет-сервисы`, `Стриминговые сервисы`|На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.| Сравнение Москвы и Петербурга окружено мифами:</br> - Москва — мегаполис, подчинённый жёсткому ритму рабочей недели;</br> - Петербург — город своеобразной культуры, непохожий на Москву.</br> Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки проверила данные и сравнила поведение пользователей двух столиц.|`python`, `pandas`|



