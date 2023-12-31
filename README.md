# pet_project_bookings-danielcheeky-s 
Проект выполнен на языке python в Jupiter Notebook с использованием библиотеки pandas, дан файл 'bookings.csv' с данными по бронированиям отелей. 
Мне предстояло ответить на следующие вопросы и задачи:
  1) Импортируйте библиотеку pandas как pd. Загрузите датасет bookings.csv с разделителем ;. Проверьте размер таблицы, типы переменных, а затем выведите первые 7 строк, чтобы посмотреть на данные.
  2) Приведите названия колонок к нижнему регистру и замените пробелы на знак нижнего подчеркивания.
  3) Пользователи из каких стран совершили наибольшее число успешных бронирований? Укажите топ-5.
  4) На сколько ночей в среднем бронируют отели разных типов?
  5) Иногда тип номера, полученного клиентом (assigned_room_type), отличается от изначально забронированного (reserved_room_type). Такое может произойти, например, по причине овербукинга. Сколько подобных наблюдений встретилось в датасете?
  6) Проанализируйте даты запланированного прибытия.
  6.1) На какой месяц чаще всего успешно оформляли бронь в 2016? Изменился ли самый популярный месяц в 2017?
  6.2) Сгруппируйте данные по годам и проверьте, на какой месяц бронирования отеля типа City Hotel отменялись чаще всего в каждый из периодов.
  7) Посмотрите на числовые характеристики трёх переменных: adults, children и babies. Какая из них имеет наибольшее среднее значение?
  8) Создайте колонку total_kids, объединив children и babies. Отели какого типа в среднем пользуются большей популярностью у клиентов с детьми?
  9) Создайте переменную has_kids, которая принимает значение True, если клиент при бронировании указал хотя бы одного ребенка (total_kids), и False – в противном случае.
  Посчитайте отношение количества ушедших пользователей к общему количеству клиентов, выраженное в процентах (churn rate). Укажите, среди какой группы показатель выше.
