# Коран — Telegram Mini App

Один файл `index.html`, без сборки. Данные берутся из открытых API:
- суры: api.quran.com (названия, число аятов)
- чтецы и аудио целых сур: mp3quran.net (ссылка = server + номер суры из 3 цифр + .mp3)

## Как запустить в Telegram
1. Выложите папку на HTTPS-хостинг: проще всего https://app.netlify.com/drop (перетащить папку) или GitHub Pages / Cloudflare Pages. Получите ссылку вида https://имя.netlify.app
2. В Telegram откройте @BotFather → /newbot → создайте бота.
3. /newapp (или /mybots → бот → Bot Settings → Menu Button) → укажите ссылку из шага 1.
4. Откройте бота и нажмите кнопку меню — приложение запустится.
