marketplace-delivery-system/
│
├── README.md                  # Главный документ проекта (описание, цели, архитектура)
│
├── api/                       # Все, что связано с API
│   └── openapi.yaml           # Ваш файлик спецификации OpenAPI 3.0
│
├── diagrams/                  # Все диаграммы и схемы
│   ├── bpmn/                  # Диаграммы бизнес-процессов
│   │   ├── process_to_be.png  # Экспортированная картинка схемы BPMN 2.0
│   │   └── process_to_be.bpmn # Исходник (для Camunda/Draw.io)
│   ├── uml/                   # Диаграммы UML
│   │   └── state_machine.png  # Диаграмма состояний заказа
│   └── erd/                   # Диаграмма базы данных
│       └── database_erd.png
│
├── docs/                      # Текстовые требования
│   ├── user-stories.md        # User Stories и Нефункциональные требования (NFR)
│   └── use-cases.md           # Подробные сценарии использования
│
└── sql/                       # SQL-скрипты
    └── create_tables.sql      # Примеры DDL/DML запросов
