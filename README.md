# Melon Android

Android-клиент Watermelon Messenger.

Репозиторий для отдельной разработки; рядом с основным проектом:

```
Documents/
├── melon-messenger/   # API, web, deploy
├── melon-ios/
├── melon-android/     # этот репозиторий
└── melon-infra/
```

## Статус

Заготовка под будущее приложение. Код ещё не переносился из монорепозитория.

## API (когда начнёте)

- REST: `{baseURL}/api`
- WebSocket: `{baseURL}/ws`
- Auth: OAuth Yandex → JWT (`GET /auth/yandex?platform=native`, `POST /auth/yandex/exchange`)

Подробности по OAuth — в [melon-ios/YANDEX_OAUTH.md](../melon-ios/YANDEX_OAUTH.md).
