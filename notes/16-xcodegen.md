# Проект Xcode из project.yml

Если .xcodeproj не хранится в git, его создаёт XcodeGen: xcodegen generate --spec ios/project.yml. Файл проекта пересоздаётся одинаково на любой машине и не даёт конфликтов при слиянии.
