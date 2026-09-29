# С Windows на Mac: концы строк

Репозиторий из Windows показывает сотни «изменённых» файлов из-за CRLF. git config --global core.autocrlf input — git сравнивает без учёта концов строк, новые коммиты уходят с LF.
