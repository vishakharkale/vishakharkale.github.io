```mermaid
flowchart TD
    subgraph Invoice_Reception
        A[Paper Invoices]
        B[PDF/Image Invoices]
        C[Email Invoices]
    end
    subgraph Data_Extraction
        D[OCR for Paper/PDF/Image]
        E[Direct Extraction from Email]
    end
    F[Data Validation AI ML]
    G[Centralized Storage DMS]
    H[Review UI Human Interaction]
    I[Review and Approval Workflow Automated, AI/ML]
    J[ERP Integration Automatic Invoice Creation]
    K[Monitoring and Tracking Real-time]
    L[Notifications At Key Points in Process]
    M[Reporting and Dashboards Comprehensive Insights]

    A --> D
    B --> D
    C --> E
    D --> F
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    J --> K
    K --> L
    L --> M
    G --> I
