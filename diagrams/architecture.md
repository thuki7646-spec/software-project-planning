# System Architecture Diagram

```mermaid
flowchart LR
    U[👤 Users]

    subgraph FE [🖥️ Frontend]
        UI[User Interface]
    end

    subgraph BE [⚙️ Backend / API]
        API[REST API]
    end

    subgraph DB [🗄️ Database]
        DATA[(Data)]
    end

    U --> UI
    UI --> API
    API --> DATA
    DATA --> API
    API --> UI
    UI --> U
