# Описание проектов выполненых во время обучения в Яндекс.Практикуме на курсе "Data Science"


| Проект | Задачи проекта |	Описание работы | Навыки и библиотеки |
| :--------------- | :--------- | :------------------------------ | :--------- |
| с выравниванием слева | с выравниванием справа | и с выравниванием по центру | и с выравниванием по центру |
| [1. Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов][1] | На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга. | Сравнение Москвы и Петербурга окружено мифами: - Москва — мегаполис, подчинённый жёсткому ритму рабочей недели; - Петербург — город своеобразной культуры, непохожий на Москву. Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки вы проверите данные и сравните поведение пользователей двух столиц.  | Python, Pandas, Numpy, Matplotlib, обработка данных, дубликаты, пропуски, логическая индексация, группировка, сортировка| 
| [2. Исследование надёжности заёмщиков — анализ банковских данных][2]  | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. | Python, Pandas, Numpy, PyMystem3, Matplotlib, Seaborn,  предобработка данных, дубликаты, пропуски, категоризация, декомпозиция |
| [3. Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости][3] | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | Python, Pandas, Numpy, Matplotlib, Seaborn, визуализация данных, исследовательский анализ данных, предобработка данных, обработка данных, histogram, boxplot, scattermatrix, категоризация, scatterplot,  фрод-мониторинг |
| [4. Определение выгодного тарифа для телеком компании][4] | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | Python, Pandas, Numpy, Matplotlib, Seaborn, Math, Scipy, описательная статистика, проверка статистических гипотез, обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента |
| [5. Определение перспективного продукта в индустрии реализации компьютерных игр][5] | Предобработка данных; анализ данных; составление портрета пользователей каждого региона; проверка гипотез; выявление параметров, определяющих успешность видеоигр в разных регионах мира; подготовка отчета в целях планирования рекламных кампаний для магазина компьютерных игр | Интернет-магазин «Стримчик» продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. | Python, Pandas, Numpy, Matplotlib, Seaborn, PyMystem3, Scipy, исследовательский анализ данных, описательная статистика, предобработка данных, проверка статистических гипотез |
| [6. Классификаиция клиентов телеком компании][6] | На основе данных предложить клиенту тариф. | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф. | Python, Pandas, Matplotlib, Seaborn, классификация, подбор гиперпараметров, выбор модели МО |
| [7. Прогнозирование оттока клиента Банка][7] | На основе данных из банка определить клиента, который может уйти | Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. | Python, Pandas, Numpy, Matplotlib, Seaborn, классификация, подбор гиперпараметров, выбор модели МО|
| [8. Определение наиболее выгодного региона нефтедобычи][8]  | На основе данных геологи разведки выбрать район добычи нефти | Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. |Matplotlib, Numpy, Pandas, Seaborn, Scipy, Sklearn, Bootstap, регрессия, разработка бизнес-модели, бутстреп |
| [9. Исследование технологического процесса очистки золота][9] | Спрогнозировать концентрацию золота при проведении процесса очистки золота | Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. | Matplotlib,NumPy,Pandas,Python,Scikit-learn,исследовательский анализ данных, визуализация данных, анализ данных, регрессия, кастомные метрики |
| [10. Защита данных клиентов страховой компании][10] | Разработка модели анонимизации персональных данных | Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется. | NumPy,Python,Scikit-learn, линейная алгебра, регрессия |
| [11. Построение модели определения стоимости автомобиля][11] | Разработка системы рекомендации стоимости автомобиля на основе его описания | Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля. | Pandas,Python,lightgbm, Catboost, градиентный бустинг, регрессия |
| [12. Прогнозирование количества заказов такси на следующий час][12]  | Разработка системы предсказания объема заказа. | Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания. | Python, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, Scipy, классификация, кластеризация, машинное обучение, временные ряды, регрессия, предсказания |
| [13. Обучение модели классификации комментариев][13] | Определение токсичности комментарии. | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. | BERT,Pandas,Python,nltk,tf-idf, обработка естественного языка, NLP |
| [14. Обработка фотографий покупателя][14]  | Определение возраста по фотографии | Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста. | Keras,Python, обработка изображени, нейронные сети |
| [15. Построение модели предсказания оттока клиентов для телекоммуникационной компании "ТелеДом"][15] | обучить на данных модель для прогноза оттока клиентов телекоммуникационной компании "ТелеДом" | Оператор телекоммуникационной компании "ТелеДом" хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. | Python, Pandas, Numpy, Scikit-learn, PyMystem3, Matplotlib, Seaborn, Scipy, Tableau, предобработка данных, исследовательский анализ данных,классификация, лемматизация, классификация, проверка статистических гипотез, продуктовые метрики, визуализация данных, построение дашбордов

[1]:https://github.com/Eindestar/portfolio/blob/main/Project_1
[2]:https://github.com/Eindestar/portfolio/tree/main/Project_2
[3]:https://github.com/Eindestar/portfolio/tree/main/Project_3
[4]:https://github.com/Eindestar/portfolio/tree/main/Project_4
[5]:https://github.com/Eindestar/portfolio/tree/main/Project_5
[6]:https://github.com/Eindestar/portfolio/tree/main/Project_6
[7]:https://github.com/Eindestar/portfolio/tree/main/Project_7
[8]:https://github.com/Eindestar/portfolio/tree/main/Project_8
[9]:https://github.com/Eindestar/portfolio/tree/main/Project_9
[10]:https://github.com/Eindestar/portfolio/tree/main/Project_10
[11]:https://github.com/Eindestar/portfolio/tree/main/Project_11
[12]:https://github.com/Eindestar/portfolio/tree/main/Project_12
[13]:https://github.com/Eindestar/portfolio/tree/main/Project_13
[14]:https://github.com/Eindestar/portfolio/tree/main/Project_14
[15]:https://github.com/Eindestar/portfolio/tree/main/Project_final
