# 3x-ui Subpage

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Статическая страница подписки для панели [3x-ui](https://github.com/MHSanaei/3x-ui): отображение конфигов, QR-кодов и ссылок для клиентов.

## Особенности

- Одностраничный `index.html` без сборки
- Тёмная тема, QR-коды, анимация фона
- Сама запрашивает содержимое подписки по собственному URL (заголовок `Accept: text/plain`) — рассчитана на reverse proxy (nginx/Caddy), который отдаёт эту страницу браузеру, а сырой конфиг — клиентским приложениям

## Быстрый старт

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/renkagod/3xui-subpage.git
   cd 3xui-subpage
   ```

2. Разместите файлы на веб-сервере (корень сайта или подкаталог).

3. Настройте панель 3x-ui и подписку по [официальной вики](https://github.com/MHSanaei/3x-ui/wiki).

## Структура

| Путь | Назначение |
|------|------------|
| `index.html` | Страница подписки |

## Документация

Подробная настройка панели и подписок — в вики 3x-ui (см. ссылку выше).

## Лицензия

[MIT](LICENSE) — Copyright (c) 2026 [renkagod](https://github.com/renkagod).
