# docs-architecture-diagrams
ОСНОВЫ РАБОТЫ С ТЕХНИЧЕСКОЙ ДОКУМЕНТАЦИЕЙ
# Документация: Архитектурные диаграммы

Примеры диаграмм через Mermaid.

## Схема сервиса
```mermaid
graph TD
  A[Клиент] --> B[API Gateway]
  B --> C[Auth Service]
  B --> D[User Service]
  B --> E[Order Service]
  D --> F[(PostgreSQL)]
  E --> F
  E --> G[(Redis)]
