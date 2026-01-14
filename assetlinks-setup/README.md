# BarvaPay Digital Asset Links

Этот репозиторий содержит файл `assetlinks.json` для работы Passkey в приложении BarvaPay.

## Как использовать

1. Создайте новый репозиторий на GitHub
2. Загрузите содержимое этой папки в репозиторий
3. Включите GitHub Pages:
   - Settings → Pages → Source: Deploy from a branch
   - Branch: main / root
4. Дождитесь деплоя (1-2 минуты)
5. Проверьте: `https://YOUR_USERNAME.github.io/REPO_NAME/.well-known/assetlinks.json`

## Важно

- Замените `YOUR_USERNAME` на ваш GitHub username
- SHA256 fingerprint в файле соответствует debug-ключу
- Для production нужно добавить fingerprint release-ключа
