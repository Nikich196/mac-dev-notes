# PostgreSQL и PostGIS через Homebrew

`brew install postgresql@17 postgis` — сервер и расширение для геоданных (сам сервер PostGIS не ставит). `brew services start postgresql@17` — запустить. В нужной базе: `CREATE EXTENSION postgis;`, проверка — `SELECT postgis_version();`.
