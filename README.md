GET /api/ev/station/list
Получение всех доступных зарядных станций

GET /api/ev/station/get/{id}
Получение зарядной станции по идентификатору

GET /api/ev/station/active
Получение списка активных станций

GET /api/ev/station/partner
Получение списка активных станций


POST
/api/ev/charge/price_anticipate
Получение примерной стоимости зарядки
POST
/api/ev/charge/price_final
Получение окончательной стоимости зарядки
POST
/api/ev/charge/start
Начало сесссии зарядки
POST
/api/ev/charge/reserve
Резервирование коннектора
POST
/api/ev/charge/stop
Завершение сесссии зарядки
POST
/api/ev/charge/continue
Продление сесссии зарядки
POST
/api/ev/charge/status
Получение информации о сесссии зарядки
GET
/api/ev/charge/history
Получение истории сессий зарядок
POST
/api/ev/charge/start_rfid
Начало сесссии зарядки по id tag
POST
/api/ev/charge/stop_rfid
Начало сесссии зарядки по id tag
GET
/api/ev/charge/session/active
Получение списка автивных сессий
