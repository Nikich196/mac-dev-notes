# Где лежат файлы приложения в симуляторе

`xcrun simctl get_app_container booted <bundle id> data` печатает путь к папке с данными приложения (Documents, Library). `open "$(xcrun simctl get_app_container booted <bundle id> data)"` откроет её в Finder.
