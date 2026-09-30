# Разрешения без всплывающих окон

`xcrun simctl privacy booted grant location <bundle id>` — выдать приложению доступ к геопозиции (также `photos`, `microphone`, `contacts`, `calendar`). `revoke` — отозвать, `xcrun simctl privacy booted reset all` — снова задавать вопросы.
