<div align="center">
  <img src="./logo.svg" alt="NextCore Revolution Corp" width="520" />
  <br/><br/>

  **Plataforma modular de gestión empresarial para Chile 🇨🇱**

  [![Stack](https://img.shields.io/badge/Stack-Django%20+%20React%20+%20PostgreSQL-067660?style=flat-square)](https://github.com/nextCoreRevolutionCorp)
  [![Status](https://img.shields.io/badge/Status-Active%20Development-62ff99?style=flat-square&labelColor=067660)](https://github.com/nextCoreRevolutionCorp)
  [![Docs](https://img.shields.io/badge/Docs-ncr--learning-06ae73?style=flat-square)](https://github.com/NextCoreRevolutionCorp/ncr-learning)
</div>

---

## ¿Qué es Next Core?

**Next Core** es nuestra plataforma — el SDK que revoluciona cómo se construyen portales de gestión empresarial en Chile. Un nuevo proyecto cliente arranca en días, no semanas, porque el 80% del código ya existe en la plataforma.

```
┌────────────────────────────────────────────────────────────────┐
│                      NEXT CORE PLATFORM                        │
│                                                                │
│   ncr-core (Python SDK)  │  ncr-ui-kit (React)  │  ncr-infra  │
└──────────────────────────┬─────────────────────────────────────┘
                           │
         ┌─────────────────┼──────────────────┐
         ▼                 ▼                  ▼
   dagc-backend      dirper-backend      saas-backend
   dagc-frontend     dirper-frontend     saas-frontend
   (UdeC DAGC)       (UdeC DIRPER)       (NCR SaaS)
```

> **Thin clients, fat platform.** Los proyectos cliente solo tienen config, branding, y lógica de negocio específica. Todo lo demás vive aquí.

---

## 📦 Plataforma SDK

| Repo | Qué hace |
|------|----------|
| [**ncr-core**](https://github.com/NextCoreRevolutionCorp/ncr-core) | Python/Django SDK — auth JWT, RBAC, middleware, modelos base, utils chilenos (RUT, fechas) |
| [**ncr-ui-kit**](https://github.com/NextCoreRevolutionCorp/ncr-ui-kit) | React component library — DataTable, Modal, Sidebar, Card, design tokens, 3 temas |
| [**ncr-devkit**](https://github.com/NextCoreRevolutionCorp/ncr-devkit) | CLI — `ncr new project --type=dagc` genera un proyecto listo en segundos |
| [**ncr-infra**](https://github.com/NextCoreRevolutionCorp/ncr-infra) | Templates Docker, nginx, GitHub Actions para todos los proyectos |
| [**ncr-learning**](https://github.com/NextCoreRevolutionCorp/ncr-learning) | Documentación, arquitectura, onboarding, CONTRIBUTING |

## 🏛️ Proyectos Cliente

| Repo | Cliente | Descripción |
|------|---------|-------------|
| [dagc-frontend](https://github.com/NextCoreRevolutionCorp/dagc-frontend) / [backend](https://github.com/NextCoreRevolutionCorp/dagc-backend) | UdeC DAGC | Portal de contrataciones públicas — single-tenant |
| [dirper-frontend](https://github.com/NextCoreRevolutionCorp/dirper-frontend) / [backend](https://github.com/NextCoreRevolutionCorp/dirper-backend) | UdeC DIRPER | Portal de gestión de contratos de personal — single-tenant |
| [saas-frontend](https://github.com/NextCoreRevolutionCorp/saas-frontend) / [backend](https://github.com/NextCoreRevolutionCorp/saas-backend) | NCR SaaS | Plataforma de procurement — multi-tenant |

---

## 🛠️ Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2+-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 🚀 Nuevo aquí?

```bash
# 1. Lee la doc (5 min)
open https://github.com/NextCoreRevolutionCorp/ncr-learning

# 2. Clona lo que necesitas
git clone git@github.com:NextCoreRevolutionCorp/ncr-learning.git
git clone git@github.com:NextCoreRevolutionCorp/ncr-core.git

# 3. Lee CONTRIBUTING.md
```

---

<div align="center">
  <sub>© 2025 NextCore Revolution Corp · Concepción, Chile 🇨🇱</sub>
</div>
