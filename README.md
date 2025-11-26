```mermaid
flowchart TD
    %% ========= LÉGENDE GLOBALE =========
    classDef year fill:#05080b,stroke:#00f6ff,stroke-width:2px,color:#00f6ff;
    classDef phase fill:#070b10,stroke:#444,stroke-width:1.5px,color:#ffffff;
    classDef item fill:#0c1117,stroke:#333,stroke-width:1px,color:#d0d0d0;

    %% ========= 2025 — IDENTITY LAYER =========
    Y2025[2025 — Identity Layer]:::year

    P1[Phase 1 — Aeon ID<br/>New identity architecture]:::phase
    P1A[Define identity model<br/>Flows • objects • guarantees]:::item
    P1B[Local cryptography engine<br/>Keys • signatures • offline model]:::item
    P1C[Secure flows<br/>Auth • sessions • approvals]:::item
    P1D[Minimal backend trust layer<br/>Verification • policies]:::item
    P1E[Public docs & concept repo<br/>aeon-id (public)]:::item

    Y2025 --> P1
    P1 --> P1A --> P1B --> P1C --> P1D --> P1E

    %% ========= 2026 — ERP FOUNDATION =========
    Y2026[2026 — ERP Foundation]:::year

    P2[Phase 2 — Aeon ERP Core<br/>Operational backbone]:::phase
    P2A[Core data model<br/>Entities • relations • stability]:::item
    P2B[Modules v1<br/>Projects • Tasks • CRM • Simple finance]:::item
    P2C[Workflow engine<br/>Events → Conditions → Actions]:::item
    P2D[Identity integration<br/>Aeon ID → roles & permissions]:::item
    P2E[Internal usable ERP<br/>Aeon uses its own system]:::item

    P1E --> Y2026
    Y2026 --> P2
    P2 --> P2A --> P2B --> P2C --> P2D --> P2E

    %% ========= 2026 — INFRA LAYER =========
    YINFRA[2026 — Infrastructure Layer]:::year

    P3[Phase 3 — Internal Infrastructure]:::phase
    P3A[Aeon Vault (base)<br/>Encrypted storage • secrets]:::item
    P3B[Aeon Chain (base)<br/>Ledger • audit • signed events]:::item
    P3C[Cloud planning<br/>APIs • deployment model • topology]:::item

    P2E --> YINFRA
    YINFRA --> P3
    P3 --> P3A --> P3B --> P3C

    %% ========= 2026 Q3/Q4 — PRODUCT LAUNCH =========
    YLAUNCH[2026 Q3–Q4 — Product Launch]:::year

    P4[Phase 4 — Commercial ERP]:::phase
    P4A[ERP UI & UX<br/>Clean interface for real users]:::item
    P4B[Beta program<br/>Early partners • feedback loop]:::item
    P4C[Docs & onboarding<br/>Guides • flows • support basics]:::item
    P4D[First paying customers<br/>Starter plan • small teams]:::item

    P3C --> YLAUNCH
    YLAUNCH --> P4
    P4 --> P4A --> P4B --> P4C --> P4D

    %% ========= 2027+ — EXPANSION =========
    YEXP[2027+ — Expansion]:::year

    P5[Phase 5 — Expansion & Scale]:::phase
    P5A[Advanced ERP modules<br/>HR • Inventory • Planning • Budgeting]:::item
    P5B[Aeon Vault v2<br/>Deeper integrations • approvals]:::item
    P5C[Aeon Chain v2<br/>Richer events • automation hooks]:::item
    P5D[Aeon Cloud v1<br/>Unified hosting • infra orchestration]:::item

    P4D --> YEXP
    YEXP --> P5
    P5 --> P5A --> P5B --> P5C --> P5D
```
