# Sentinel Platform | Architecture Diagram

```mermaid
flowchart TD
 A[Web Interface] --> B[Audit Orchestrator]
 B --> C[Network Analysis]
 B --> D[Wi-Fi Security]
 B --> E[Device Intelligence]
 B --> F[Analysis Agents]
 C --> G[Security Scoring]
 D --> G
 E --> G
 F --> G
 G --> H[Executive Dashboard]
 H --> I[PDF Reports]
 I --> J[Audit History]
```

Conceptual architecture for public documentation.
