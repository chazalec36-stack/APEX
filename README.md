flowchart TD
    %% Node Definitions and Roles
    A[Project Sponsor<br/>CCWS]
    B[Faculty Advisor<br/>Jeff]
    C[Project Manager<br/>Leo Li]
    D[Strategic Consulting<br/>Chaz Alec]
    E[Community Liaison<br/>Sarah]
    F[Tech Support Leads<br/>Jordan & Alex]

    %% Hierarchy Connections
    A -->|Approves & Funds| C
    B -.->|Academic Oversight| C
    
    C -->|Coordinates| D
    C -->|Coordinates| E
    C -->|Coordinates| F

    %% Optional Styling for visual hierarchy
    classDef sponsor fill:#e1bee7,stroke:#8e24aa,stroke-width:2px;
    classDef advisor fill:#fff9c4,stroke:#fbc02d,stroke-width:2px,stroke-dasharray: 5, 5;
    classDef manager fill:#bbdefb,stroke:#1e88e5,stroke-width:2px;
    classDef team fill:#c8e6c9,stroke:#43a047,stroke-width:2px;

    class A sponsor;
    class B advisor;
    class C manager;
    class D,E,F team;
