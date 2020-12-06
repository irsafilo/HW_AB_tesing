# HW_AB_tesing


Представьте, что у нас небольшой магазин, куда приходят покупатели, делают покупки и мы можем посчитать их средний чек за день. Также допустим у нас покупатели закупаются раз в 10 дней из-за выгодных предложений, акций, сезонности, скидок и по каким-то еще неведомым нам причинам. У нас есть исторические данные - user_id, metric, day. metric - cредний чек покупателя, user_id - айдишник покупателя, day - день покупок клиента. У нас 10к покупателей, которые были в магазине 2 раза в прошлом месяце. Мы построили модель, повышающую средний чек у покупателей, и теперь хотим проверить, как она работает. Для этого нам надо правильно спланировать А/Б тест.
Данные лежат "./data/df_hw.csv".

Задание:

Вам нужно подобрать дизайн корректного А/Б теста на исторических данных и ответить на следующие вопросы:

1) Можно ли статистически значимо задетектить эффект в 2%? Если можно, то за какую длительность теста?

2)* Если можно, то за какую длительность теста?
