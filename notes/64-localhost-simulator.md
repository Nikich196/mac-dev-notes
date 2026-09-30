# localhost в симуляторе iPhone

Симулятор использует сеть Mac, поэтому `http://localhost:5000` из приложения попадает на сервер, запущенный на этом же Mac. Настоящему iPhone нужен адрес Mac в Wi-Fi: `ipconfig getifaddr en0`.
