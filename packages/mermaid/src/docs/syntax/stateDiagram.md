graph TD
    A[Gerente General] --> B[Director de Producción]
    A --> C[Gerente de Ventas y Marketing]
    A --> D[Gerente Legal]
    A --> E[Gerente Financiero]
    A --> F[Gerente de Recursos Humanos]
    
    B --> B1[Jefe de Planta]
    B --> B2[Responsable de Control de Calidad]
    B --> B3[Analista de Producción]
    B1 --> B1a[Supervisores de Línea]
    B1 --> B1b[Técnicos de Mantenimiento]
    B1a --> B1a1[Operarios de Producción]
    
    C --> C1[Gerente de Diseño Textil]
    C --> C2[Jefe de Logística]
    C --> C3[Jefe de Ventas]
    C1 --> C1a[Diseñadores Textiles]
    C2 --> C2a[Coordinador de Almacén]
    C2 --> C2b[Coordinador de Distribución]
    C3 --> C3a[Ejecutivos de Ventas]
    C3 --> C3b[Servicio al Cliente]
    
    D --> D1[Asesores Legales]
    D --> D2[Coordinador de Cumplimiento Normativo]
    
    E --> E1[Contador General]
    E --> E2[Jefe de Costos]
    E --> E3[Analista Financiero]
    E1 --> E1a[Asistentes Contables]
    
    F --> F1[Coordinador de Selección]
    F --> F2[Coordinador de Capacitación]
    F --> F3[Analista de Nómina]
    
    A --> G[Coordinador de Sostenibilidad]
    G --> G1[Analista Ambiental]
    
    A --> H[Jefe de Sistemas]
    H --> H1[Soporte Técnico]
    H --> H2[Analista de Sistemas]

    style A fill:#f9d5e5
    style B,C,D,E,F fill:#eeac99
    style B1,B2,B3,C1,C2,C3,D1,D2,E1,E2,E3,F1,F2,F3,G,H fill:#d6eaf8
