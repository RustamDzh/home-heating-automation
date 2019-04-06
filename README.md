# home-heating-automation
Автоматизация отопления загородного дома

Предпологается управление котлом, циркуляционными насосами, клапанами на "гребенке", клапанами на батареях.
Управление котлом, насосами и клапанами на гребенке будет осущетсвялться через ПЛК. 
Так же к ПЛК будет подключена плата ESP32,  в комнатах будут установлены платы ESP8266, которые будут измерять температуру в комнатах,
передавать показания на esp32, принимать команды управления батареями и управлять клапанами, передавать на ESP32 уставки для поддержания требуемой
температуры. 
Связь будет построена на основе mesh сети.У головного esp32 будет web страница для управления.

Основные контуры управления:
1:ГВС
2:Баня
3:Полы 1 Этаж
4:Полы 2 Этаж
5:Батареи 1 Этаж
6:Батареи 2 Этаж
7:Прихожая

Дополнительные контуры:
1: Батарея балкон.
2: Батарея комната 21
3: Батарея комната 22
4: Батарея комната 23
5: Батарея спальня
6: Батарея зал+кухня

Зоны регулирования
1: Бяня (пол+батареи вместе)
2: Прихожая (пол+батареи вместе)
3: Зал+кухня (пол+батареи раздельно)
4: Спальня  (пол+батареи раздельно)
5: Санузел 1 э. пол
6: Санузел 2 э. пол
7: 2 Этаж, балкон (батарея)
8: 2 Этаж, комната 21 (батарея)
9: 2 Этаж, комната 22 (батарея)
10: 2 Этаж, комната 23 (батарея)

1. Этап внедрения:
1. Подключение ПЛК.
2. Подключение комнатного термостата 1 этажа.






