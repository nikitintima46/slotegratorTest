Используются сторонние плагины. 
1. Для реализации нагрузочного профиля используются "bzm - Arrivals Thread Group" для генерации ступенчатой нагрузки в RPS и "bzm - Weighted Switch Controller" для распределения между запросами.
2. Для удаления всех ранее созданных игроков используется группа потоков "tearDown Thread Group".
3. Удаление пользователей происходит в While цикле.
