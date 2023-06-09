**Описание проекта.**

В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах. Ваша задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости. О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта и ближайшего парка.

**Задачи проекта.**
Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир.

**Используемый стек.**
Python, Pandas, Matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных.

**ИТОГОВЫЙ ВЫВОД ПО ПРОЕКТУ.**

**Срок продажи квартиры** - Чаще всего квартиру продают за 95 дней. Если меньше 45 дней, то это быстро, если дольше 230 дней - это долго.
Есть большое число квартир, проданных всего за несколько дней после публикации. Также есть варианты, которые продавались несколько десятков месяцев.
**Факторы, влияющие на стоимость квартиры** - На стоимость больше влияет площадь квартиры, нежели число комнат. Т.е. могут быть дорогие квартиры с малым числом комнат, но где комнаты просторные. Первый этаж значительно дешевле остальных вариантов. Также стоимость квартиры на последнем этаже ниже, чем на остальных, кроме первого.
**Стоимость квадратного метра в топ-10 населённых пунктов** - Дороже всего квадратный метр в Санкт-Петербурге - 114848, Дешевле всего квадратный метр в Выборге - 58141
**Факторы, влияющие на стоимость в центре Санкт-Петербурга** - В центральной зоне наблюдается резкое снижение цены в зоне до 2,5 км. от центра, далее цена растет и начинает резко снижаться в раойне 7 км и выходит на отностительное плато на растоянии 9 км от центра.таким образом можно сказать что в центре города практически нет разницы, насколько квартира удалена от условного центра города.
