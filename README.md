# 🌲 Harvest Management 3.0 software system_COPY

This repository contains COPY of the source code and documentation for Harvest Management 3.0 software system.
---

## 📁 Solution Structure
```
Wagner.HarvestManagement/
├── .github/           # Github-specific content: workflows, configs, templates etc.
├── apps/              # HMS3 applications
├── docs/              # General documentation
├── .gitattributes     # Git source control configuration
└── README.md          # You're here!
```

---

## 🚀 Applications
These are self-contained software products that are composed into HMS3 software system:
- **[HMS3 Web API](apps/hms3-web-api/README.md)** - core Web API .NET application
- **[HMS3 Web Frontend](apps/hms3-web-frontend/README.md)** - Web frontend React application

---

## 📘 Documentation
- **[Technology Standards](docs/technology-standards.md)** - describes solution technology standards
- **[System Architecture](docs/system-architecture.md)** - describes high-level technical architecture
- **[Infrastructure](docs/infrastructure.md)** - describes infrastructure components
- **[Database Integration](apps/hms3-web-api/HarvestManagement.Infrastructure.Database/README.md)** - database integration overview, diagrams, migrations and middleware
  - **[HMS 2.0(Legacy) Detabase Structure](docs/assets/statement-of-work-and-diagrams.pdf)**
- **[How to Deploy](docs/how-to-deploy.md)** - describes release/deployment operations

---
