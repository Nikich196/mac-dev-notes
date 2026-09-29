# С Windows на Mac: права на запуск скриптов

Скопированные с Windows скрипты теряют флаг «исполняемый» («permission denied»). Вернуть по записям git: git ls-files -s | awk '$1=="100755"{print $4}' | xargs chmod +x.
