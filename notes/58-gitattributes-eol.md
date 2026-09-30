# Команда на Windows и Mac: единые концы строк

Файл `.gitattributes` в корне репозитория: `* text=auto eol=lf`. Тогда у всех файлы с LF, независимо от настроек компьютера. Для shell-скриптов это обязательно: с CRLF bash падает на `\r: command not found`.
