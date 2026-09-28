# Примеры диаграмм

## C4 Context
```mermaid
graph TB
  User[Пользователь] --> System[Система]
  System --> External[Внешний API]
  System --> DB[(База данных)]
