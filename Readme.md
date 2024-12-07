# Мастерская 1
Даны данные о стартапах за период с 1970 по 2018 годы.

<span style='font-size: 18px;'><b>Цель исследования</b><span>

1. Разработать модель машинного обучения для предсказания того, продолжит стартап работу или закроется.
2. Провести полноценный разведочный анализ и сформировать рекомендации будущим создателям стартапов (какие факторы влияют на успешность бизнес идеи).
<br><br>  


<span style='font-size: 18px;'><b>Описание данных</b><span>

Заказчик предоставил данные в 2 файлах: тренировочный набор (около 53 тыс. записей) и тестовый набор (около 13 тыс. записей). Тренировочный набор содержит целевой признак status, указывающий на то, закрылся стартап или продолжает действовать. Временной период - '1970-01-01' по '2018-01-01'. Дата формирования выгрузки - '2018-01-01'.

- `name` - Название стартапа
- `category_list` - Список категорий, к которым относится стартап
- `funding_total_usd` - Общая сумма финансирования в USD
- `status` - Статус стартапа (закрыт или действующий)
- `country_code` - Код страны
- `state_code` - Код штата
- `region` - Регион
- `city` - Город
- `funding_rounds` - Количество раундов финансирования
- `founded_at` - Дата основания
- `first_funding_at` - Дата первого раунда финансирования
- `last_funding_at` - Дата последнего раунда финансирования
- `closed_at` - Дата закрытия стартапа (если применимо)
<br><br>