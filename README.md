# Order System — Система управления заказами

Сквозной кейс: приём заказов, проверка остатков, оплата, уведомления, отчёты.

## Структура
- `backend/` — сервисы (Order, Inventory, Payment, Notification, Report)
- `frontend/` — HTML-форма заказа
- `shared/` — модели и логгер
- `config/` — настройки
- `tests/` — pytest, Playwright, Locust
- `docs/` — архитектура, протоколы, отчёты

## Запуск
```bash
pip install -r requirements.txt
pytest tests/ -v
