graph LR
    Frontend -->|API Request| Backend
    Backend -->|Response| Frontend
    Backend --> Database
    Database --> Backend
