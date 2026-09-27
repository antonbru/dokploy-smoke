# dokploy-smoke

Тестовый репозиторий для проверки деплой-пути на VPS `vps01` (Beget, Ubuntu 26.04) с Dokploy.

Ожидаемый путь: git clone → сборка Nixpacks → контейнер → Traefik → HTTPS (Let's Encrypt) → домен вида `smoke.preview.spchk.ru`.

Внутри только статическая страница `index.html` и `robots.txt` с запретом индексации. Секретов нет.
