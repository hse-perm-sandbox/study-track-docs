## ER-диаграмма базы данных

```mermaid
erDiagram
    users {
        integer user_id PK
        string name
        integer password_hash
        string email
    }

    category {
        integer category_id PK
        integer user_id FK
        string name
    }

    task {
        integer task_id PK
        integer user_id 
        string name
        string description
        date deadline
        integer category_id FK
        integer priority
    }

    notification {
        integer notification_id PK
        integer task_id FK
        date datetime
    }


    users ||--o{ category : "задает"
    category ||--o{ task : "содержит"
    task ||--o{ notification : "содержит"

```
