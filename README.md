# KÖRME — сайты

В репозитории находятся два статических сайта:

- Основной сайт: `main-website/`
- Рекламный сайт: `advertising-website/`

После публикации через GitHub Pages они доступны по адресам:

- `https://saduaqass.github.io/korme-websites/main-website/`
- `https://saduaqass.github.io/korme-websites/advertising-website/`

GitHub Actions публикует обе папки при каждом обновлении ветки `main`.

## Ограничение формы

Форма предзаказа рекламного сайта отправляет данные на `/api/preorder`. GitHub Pages обслуживает только статические файлы, поэтому для приёма заявок потребуется отдельно подключить API.
