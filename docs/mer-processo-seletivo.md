# Teste Mermaid

```mermaid
erDiagram
    CLIENTE ||--o{ PEDIDO : faz
    CLIENTE {
        int id
        string nome
    }
    PEDIDO {
        int id
        int cliente_id
    }
```
