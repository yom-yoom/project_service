# 📦 Project Service

## 📄 Описание

Микросервис отвечает за управление проектами пользователей. Он позволяет создавать проекты, подпроекты, управлять их структурой: создавать команду проекта, добавлять файлы, встречи, вакансии, стадии, компанию, организовывать фандрайзинг, принимать пожертвования, создавать задачи проекта и интегрировать их с Jira

## ⚙️ Технологии

### Основа:

- Java 17
- Spring Boot 3.0.6

### Базы:

- PostgreSQL
- Redis
- Liquibase

### Общение микросервисов:

- Kafka
- OpenFeign

### Тестирование:

- JUnit 5
- Mockito
- AssertJ
- Testcontainers

### Прочее:

- Lombok
- MapStruct
- Springdoc OpenAPI
- CI Pipeline (GitHub Actions)
- JaCoCo
- Slf4j
- Docker
- WebClient

## 🔗 Связанные сервисы

- Notification Service – для отправки email/sms/telegram уведомлений
- Analytics Service - для сбора и анализа данных проектов
- Achievement Service - для управления достижениями пользователей, связанных с их проектами
- Post Service - для управления постами, которые организуют проекты
- Payment Service - для запроса пожертвований
- User Service - для управления пользователями и их ролями в проектах
