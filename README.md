# видио — страницы личного Gmail-приложения

Публичное описание и политика конфиденциальности для OAuth-приложения «видио». Статический сайт без форм, аналитики, cookies и сторонних скриптов. Почтовые данные и секреты не размещаются в этом репозитории.

## Публикация

В GitHub: Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.

После успешной публикации ожидаемые адреса для репозитория `dolepp/vidio-gmail-pages`:

- Главная: https://dolepp.github.io/vidio-gmail-pages/
- Политика: https://dolepp.github.io/vidio-gmail-pages/privacy.html
- Authorised domains: `dolepp.github.io` (без протокола и пути).

В Google Cloud → Google Auth Platform → Branding укажите эти адреса только после проверки их доступности. Имя приложения должно соответствовать названию на сайте: «видио».

Google может запросить подтверждение владения доменом. Размещение на GitHub Pages само по себе не гарантирует прохождение проверки. Если `dolepp.github.io` не удаётся подтвердить, потребуется свой домен, например поддомен lainos.ru, привязанный к Pages, и подтверждение в Search Console.

Публикация сайта не меняет OAuth-статус автоматически: после сохранения Branding нужно отдельно переключить Audience → Publish app и проверить статус In production. Затем заново выдать Gmail-доступ, чтобы не использовать токен, выданный в Testing.
