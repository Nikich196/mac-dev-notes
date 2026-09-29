# Поставить и запустить приложение в симуляторе

xcrun simctl install booted путь/к/App.app, затем xcrun simctl launch booted <bundle id>. Bundle id можно узнать: /usr/libexec/PlistBuddy -c "Print :CFBundleIdentifier" App.app/Info.plist.
