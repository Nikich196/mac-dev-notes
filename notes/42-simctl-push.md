# Тестовое push-уведомление

Файл `payload.json`: `{"aps":{"alert":"Привет","sound":"default"}}`. Команда `xcrun simctl push booted <bundle id> payload.json` покажет уведомление в симуляторе — без сервера и сертификатов.
