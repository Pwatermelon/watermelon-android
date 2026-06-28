# Melon Android

Android-клиент Watermelon Messenger.

Отдельный репозиторий того же проекта:

| Репозиторий | Назначение |
|-------------|------------|
| [melon-messenger](https://github.com/Pwatermelon/melon-messenger) | API, web, deploy |
| [watermelon-ios](https://github.com/Pwatermelon/watermelon-ios) | iOS / macOS |
| [watermelon-android](https://github.com/Pwatermelon/watermelon-android) | Android (этот) |
| melon-infra | Инфраструктура (будущее) |

## Статус

Заготовка под будущее приложение. Код ещё не переносился из монорепозитория.

## API (когда начнёте)

- REST: `{baseURL}/api`
- WebSocket: `{baseURL}/ws`
- Auth: OAuth Yandex → JWT (`GET /auth/yandex?platform=native`, `POST /auth/yandex/exchange`)

Подробности по OAuth — в [watermelon-ios/YANDEX_OAUTH.md](https://github.com/Pwatermelon/watermelon-ios/blob/main/YANDEX_OAUTH.md).
