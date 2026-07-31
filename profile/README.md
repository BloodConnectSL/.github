<!-- 
Change made by: Nipuna Lakruwan
Date: 2026-08-01
Added: Initial Organization Profile README
-->
<div align="center">
  <h1>🩸 BloodConnectSL</h1>
  <p><b>A decentralized, community-driven blood donation management ecosystem for Sri Lanka.</b></p>
  <p><i>100% Free. 100% Non-Profit. 100% Open Source.</i></p>
</div>

## 🌟 Our Mission
Most blood donation camps in Sri Lanka are organized by independent community groups, creating massive information asymmetry for donors who want to help. BloodConnectSL bridges that gap with a unified, hyper-local digital ecosystem. We empower NGOs, Hospitals, and Donors to connect instantly, reducing blood wastage and ensuring life-saving logistics are highly optimized.

## 🏗️ Architecture & Core Repositories
Our system is built using enterprise-grade Clean Architecture principles, ensuring massive scalability and strict adherence to the **Sri Lanka Personal Data Protection Act (PDPA)**.

- 📱 **[mobile-app](https://github.com/BloodConnectSL/mobile-app)**: The Flutter-based donor client. Features PostGIS geospatial camp discovery and dynamic QR authentication.
- ⚙️ **[common-app-backend](https://github.com/BloodConnectSL/common-app-backend)**: Highly concurrent Go (Golang) microservice handling complex business logic and Apache Casbin RBAC.
- 🗄️ **[database](https://github.com/BloodConnectSL/database)**: Supabase PostgreSQL instance utilizing strict Row Level Security (RLS) policies at the kernel level for maximum data privacy.
- 🖥️ **[web-dashboard](https://github.com/BloodConnectSL/web-dashboard)**: Administrative React/Next.js portal for event management and clinical verifications.

## 🤝 Contributing
We strictly enforce an enterprise CI/CD pipeline. 
1. **No direct commits to `main`**.
2. All pull requests must pass automated linting and testing via GitHub Actions.
3. Every PR must be approved by the core maintainers (`@Nipuna-Lakruwan` or Vimukthi).

### "Donate Blood, Save a Life."
