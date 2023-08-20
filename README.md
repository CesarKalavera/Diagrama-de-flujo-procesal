```mermaid
graph TD
    A[Inicio] --> B[Fase Administrativa]
    B --> C[Solicitud de extradición]
    B --> D[Evaluación por SRE]
    D --> E[Transmisión a la FGR]
    D --> F[Revisión por la FGR]
    F --> G[Solicitud al juez]
    B --> H[Fase Judicial]
    H --> I[Proceso ante el juez]
    I --> J[Argumentos y defensa]
    I --> K[Decisión del juez]
    K --> L[Remisión a la SRE]
    K --> M[Decisión de la SRE]
    M --> N[Concesión de Extradición]
    N --> O[Notificación al Estado requirente]
    N --> P[Traslado por la FGR]
    M --> Q[Rehúsa de Extradición]
    Q --> R[Liberación inmediata]
    M --> S[Impugnación]
    S --> T[Juicio de amparo indirecto]
    M --> U[Revisión del Tribunal Colegiado]
    U --> V[Revisión legal y derechos humanos]
    U --> W[Confirmación o Revocación]
    W --> X[Decisión del tribunal]
    X --> Y[Fin]
