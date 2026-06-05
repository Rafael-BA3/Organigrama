flowchart TD
    A["Jefe del Centro de Cómputo"] --> B["Coordinador General de Operaciones TI"]

    B --> C["Operaciones / NOC<br/>Monitoreo 24/7, alertas y escalamiento"]
    B --> D["Infraestructura Crítica<br/>Energía, UPS, climatización y racks"]
    B --> E["Redes y Telecomunicaciones<br/>Switches, routers, enlaces y cableado"]
    B --> F["Soporte Técnico y Sistemas<br/>Usuarios, servidores y sistemas internos"]
    B --> G["Seguridad, Continuidad y Control de Acceso<br/>Acceso físico, políticas y contingencias"]

    classDef jefe fill:#0f172a,color:#ffffff,stroke:#0f172a,stroke-width:2px;
    classDef coordinador fill:#1e3a8a,color:#ffffff,stroke:#1e3a8a,stroke-width:2px;
    classDef departamento fill:#dbeafe,color:#0f172a,stroke:#2563eb,stroke-width:1.5px;

    class A jefe;
    class B coordinador;
    class C,D,E,F,G departamento;
