graph LR
    Users --> Frontend
    Frontend --> API
    API --> Database
    Database --> API
    API --> Frontend
    Frontend --> Users
