# Architecture

## High-level architecture
- Classification: CORE HEALTHCARE / CLINICAL AI
- Category: clinical-ai
- Confidence: HIGH
- Exposure risk: MEDIUM

```mermaid
    flowchart LR
        A[Web client]
    B[Scenario orchestration layer]
    C[Structured data store]
    D[Evidence service]
    E[Visualization layer]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Web client
- Scenario orchestration layer
- Structured data store
- Evidence service
- Visualization layer

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.
