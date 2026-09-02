# QA Engineer · ручное тестирование

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

Тестирую сквозные бизнес-процессы. Не отдельный экран, а весь путь заказа: от кнопки на витрине до документа в учётной системе. Работаю в e-commerce и учётных системах, специализируюсь на интеграциях.

Лучше всего у меня получается доводить дефект до слоя, а не до симптома. Я не пишу "цена в корзине неправильная". Я показываю, на каком шаге она такой стала: вот запрос, вот ответ сервиса, вот событие в брокере, вот строка в базе. Разработчику остаётся починить, а не расследовать.

## Чем занимаюсь

- **Функциональное и интеграционное** · гоняю сквозные сценарии через микросервисы, брокер и учётный контур; проверяю на всех слоях сразу, а не верю одному
- **Требования** · разбираю user story и критерии приёмки до разработки, вылавливаю противоречия и недосказанные ветки
- **Тест-дизайн** · классы эквивалентности, границы, попарное тестирование, таблицы решений
- **Документация** · чек-листы, тест-кейсы, тест-планы, баг-репорты с полным контекстом
- **Релизы** · регресс на препроде, smoke на проде после переключения трафика

## Стек

- **API** · Postman · Swagger/OpenAPI · REST · SOAP · gRPC · WebSocket · Newman
- **Данные** · PostgreSQL · ClickHouse · MongoDB · DBeaver · SQL
- **Интеграции** · Kafka · 1С · CRM
- **Наблюдаемость** · Kibana · Grafana · DevTools · Docker
- **Процесс** · Jira · Confluence · Allure TestOps · Zephyr · Figma
- **Автоматизация** · Playwright (учебные проекты)

## Опыт

### E-commerce DIY-ритейлера · с 03.2023 по 07.2026

Тестировал интернет-платформу и её связку с учётным контуром: каталог, корзину, checkout, оплату, скидки и бонусы, зоны доставки. Витрина живёт на микросервисах, внутренний контур собран на 1С и CRM, между ними Kafka.

Отвечал за путь заказа целиком. Следил, чтобы заказ создавался ровно один раз, чтобы суммы и скидки сходились во всех трёх системах, чтобы деньги не списывались дважды, а остаток на витрине совпадал с тем, что лежит на складе.

### Онлайн-бронирование билетов в кинотеатре · с 12.2021 по 02.2023

Проверял афишу, выбор места на схеме зала, бронь, оплату и финальный статус заказа. Зал обновляется в реальном времени через WebSocket, места разбирают конкурирующие пользователи. Интерфейс легко расходится с базой.

Платёжные сценарии прогонял через прокси и моки: отказ банка, таймаут, отмена, повторный запрос, некорректный статус. Реальный шлюз такие ответы по заказу не выдаёт.

## Портфолио

[**restful-booker**](https://github.com/qartyart/restful-booker-herokuapp-com-testing) · тестирование публичного учебного REST API. 112 тест-кейсов на 8 эндпоинтов, Postman-коллекция с проверками, 20 заведённых дефектов.

## Что ищу

Продуктовую команду со сложными интеграциями, где тестировщика зовут на этапе требований, а не приносят готовую сборку за день до релиза.
