# Teste Mermaid

```mermaid
erDiagram
    CLIENTE ||--o{ PEDIDO : possui

    CLIENTE {
        int id
        string nome
    }

    PEDIDO {
        int id
        int cliente_id
    }
```
