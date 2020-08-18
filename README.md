GET /api/charger/station/list
Получение всех доступных зарядных станций

GET /api/charger/station/get/{id}
Получение зарядной станции по идентификатору

GET /api/charger/station/active
Получение списка активных станций

GET /api/charger/station/partner
Получение списка активных станций


POST /api/charger/charge/price_anticipate
Получение примерной стоимости зарядки

POST /api/charger/charge/price_final
Получение окончательной стоимости зарядки

POST /api/charger/charge/start
Начало сесссии зарядки

POST /api/charger/charge/reserve
Резервирование коннектора

POST /api/charger/charge/stop
Завершение сесссии зарядки

POST /api/charger/charge/continue
Продление сесссии зарядки

POST /api/charger/charge/status
Получение информации о сесссии зарядки

GET /api/charger/charge/history
Получение истории сессий зарядок

POST /api/charger/charge/start_rfid
Начало сесссии зарядки по id tag

POST /api/charger/charge/stop_rfid
Начало сесссии зарядки по id tag

GET /api/charger/charge/session/active
Получение списка автивных сессий
