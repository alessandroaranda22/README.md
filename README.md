# Ejemplo de diagrama Mermaid

Este es un ejemplo de cómo usar Mermaid directamente en GitHub.

```mermaid
flowchart LR
  A[Inicio] --> B{¿Usuario registrado?}
  B -->|Sí| C[Mostrar panel]
  B -->|No| D[Redirigir a registro]


