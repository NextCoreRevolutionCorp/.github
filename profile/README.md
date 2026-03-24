<div align="center">

<svg width="280" height="70" viewBox="0 0 280 70" xmlns="http://www.w3.org/2000/svg">
  <rect width="280" height="70" rx="10" fill="#0A1628"/>
  <text x="16" y="44" font-family="system-ui,sans-serif" font-size="30" font-weight="700" fill="#2563EB">NCR</text>
  <text x="78" y="44" font-family="system-ui,sans-serif" font-size="17" fill="#94A3B8">NextCore Revolution</text>
  <circle cx="258" cy="35" r="11" fill="#059669" opacity="0.8"/>
  <circle cx="258" cy="35" r="5.5" fill="#34D399"/>
</svg>

# NextCore Revolution Corp

**Plataforma modular de gestión empresarial para Chile**

[![Stack](https://img.shields.io/badge/Stack-Django%20%2B%20React%20%2B%20PostgreSQL-2563EB?style=flat-square&logo=django&logoColor=white)](https://github.com/nextCoreRevolutionCorp)
[![License](https://img.shields.io/badge/License-Internal-0891B2?style=flat-square)](https://github.com/nextCoreRevolutionCorp)
[![Status](https://img.shields.io/badge/Status-Active%20Development-059669?style=flat-square)](https://github.com/nextCoreRevolutionCorp)
[![Docs](https://img.shields.io/badge/Docs-ncr--learning-475569?style=flat-square&logo=gitbook&logoColor=white)](https://github.com/nextCoreRevolutionCorp/ncr-learning)

</div>

---

## 🏗️ ¿Qué es NCR?

NextCore Revolution Corp construye **portales de gestión empresarial para instituciones públicas y privadas en Chile**. La arquitectura es una plataforma + clientes:

> **Un nuevo proyecto cliente debe poder arrancar en días, no semanas.**
> El 80% de cada proyecto es lo mismo: auth, RBAC, CRUD, layout, filtros, tablas. Todo eso vive en la plataforma. Los proyectos clientes solo agregan el 20% de diferencia.

```
┌─────────────────────────────────────────────────────────┐
│                    NCR PLATFORM (SDK)                    │
│  ncr-core (Python)  │  ncr-ui-kit (React)  │  ncr-infra │
└────────────────────────────┬────────────────────────────┘
                             │ builds on top of
         ┌───────────────────┼───────────────────┐
         ▼                   ▼                   ▼
    dagc-frontend      dirper-frontend      saas-frontend
    dagc-backend       dirper-backend       saas-backend
    (UdeC DAGC)        (UdeC DIRPER)        (NCR SaaS)
```

---

## 📦 Repositorios

### 🧱 Plataforma SDK

| Repo | Versión | Descripción |
|------|---------|-------------|
| [**ncr-core**](https://github.com/nextCoreRevolutionCorp/ncr-core) | [![v0.1](https://img.shields.io/badge/v0.1.0-059669?style=flat-square)](https://github.com/nextCoreRevolutionCorp/ncr-core) | Python/Django SDK — auth JWT, RBAC, middleware, modelos base, utils chilenos |
| [**ncr-ui-kit**](https://github.com/nextCoreRevolutionCorp/ncr-ui-kit) | [![v0.1](https://img.shields.io/badge/v0.1.0-059669?style=flat-square)](https://github.com/nextCoreRevolutionCorp/ncr-ui-kit) | React component library — Sidebar, DataTable, Modal, design tokens, theming |
| [**ncr-devkit**](https://github.com/nextCoreRevolutionCorp/ncr-devkit) | [![v0.1](https://img.shields.io/badge/v0.1.0-059669?style=flat-square)](https://github.com/nextCoreRevolutionCorp/ncr-devkit) | CLI scaffolder — `ncr new project --type=dagc` |
| [**ncr-infra**](https://github.com/nextCoreRevolutionCorp/ncr-infra) | [![stable](https://img.shields.io/badge/stable-2563EB?style=flat-square)](https://github.com/nextCoreRevolutionCorp/ncr-infra) | Docker, nginx, GitHub Actions templates |
| [**ncr-learning**](https://github.com/nextCoreRevolutionCorp/ncr-learning) | [![docs](https://img.shields.io/badge/docs-0891B2?style=flat-square)](https://github.com/nextCoreRevolutionCorp/ncr-learning) | 📚 Documentación, arquitectura, guías, ejemplos |

### 🏛️ Proyectos Cliente — UdeC

| Repo | Cliente | Tipo | Descripción |
|------|---------|------|-------------|
| [**dagc-frontend**](https://github.com/nextCoreRevolutionCorp/dagc-frontend) | UdeC DAGC | Single-tenant | Portal gestión contrataciones públicas |
| [**dirper-frontend**](https://github.com/nextCoreRevolutionCorp/dirper-frontend) | UdeC DIRPER | Single-tenant | Portal gestión contratos personal |

### 🏢 Proyectos Cliente — SaaS

| Repo | Tipo | Descripción |
|------|------|-------------|
| [**saas-frontend**](https://github.com/nextCoreRevolutionCorp/saas-frontend) | Multi-tenant | NCR Procurement SaaS — gestión abastecimiento |

---

## 🛠️ Stack Tecnológico

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2%2B-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-3.15%2B-A30000?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-18%2B-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5%2B-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5%2B-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%2B-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 🚀 Nuevo en NCR? Empieza aquí

```bash
# 1. Lee la documentación (5 minutos)
# → https://github.com/nextCoreRevolutionCorp/ncr-learning

# 2. Clona lo que necesitas
git clone git@github.com:nextCoreRevolutionCorp/ncr-learning.git
git clone git@github.com:nextCoreRevolutionCorp/ncr-core.git
git clone git@github.com:nextCoreRevolutionCorp/dagc-frontend.git  # o el proyecto que trabajes

# 3. Lee CONTRIBUTING.md en ncr-learning
# → Convenciones de commits, PRs, code review
```

📖 **[→ Documentación completa en ncr-learning](https://github.com/nextCoreRevolutionCorp/ncr-learning)**

---

## 🤝 Cómo Contribuir

1. **Lee** [`ncr-learning/CONTRIBUTING.md`](https://github.com/nextCoreRevolutionCorp/ncr-learning/blob/main/CONTRIBUTING.md) antes de hacer cualquier PR
2. **Sigue Conventional Commits**: `feat:`, `fix:`, `docs:`, `refactor:`, etc.
3. **Si es para la plataforma** → PR a `ncr-core` o `ncr-ui-kit` con tests incluidos
4. **Si es para un cliente** → PR al repo del cliente con descripción del caso de uso

> **Regla de oro:** Si algo es útil para más de un proyecto, va a la librería.

---

## 📐 Principios de Diseño

| Principio | Descripción |
|-----------|-------------|
| **Thin clients, fat platform** | Los proyectos cliente son configuración + lógica de negocio. Todo genérico va a ncr-core/ncr-ui-kit |
| **Test antes de merge** | La plataforma no se rompe. Si se rompe, todos los clientes se rompen |
| **Seguridad por defecto** | Zero Trust, JWT, RBAC en todo. Sin puertos abiertos a 0.0.0.0 |
| **Chile-first** | RUT, formatos de fecha, normativas locales: ya resueltos en ncr-core |

---

<div align="center">

**© 2025 NextCore Revolution Corp — Concepción, Chile 🇨🇱**

*Construyendo infraestructura digital para instituciones chilenas*

</div>
