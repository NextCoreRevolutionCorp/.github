<div align="center">
  <img src="./logo.svg" alt="NextCore Revolution Corp" width="480" />
  <br/><br/>

  **Plataforma modular de gestión empresarial para Chile 🇨🇱**

  [![Status](https://img.shields.io/badge/Status-Active-62ff99?style=flat-square&labelColor=067660)](https://github.com/NextCoreRevolutionCorp)
</div>

---

## Mapa de repositorios

### SDK de plataforma (dependen todos los proyectos)

| Repo | Qué hace |
|---|---|
| [ncr-ui-kit](https://github.com/NextCoreRevolutionCorp/ncr-ui-kit) | Componentes React reutilizables (layout, UI, icons, dashboard) |
| [ncr-core](https://github.com/NextCoreRevolutionCorp/ncr-core) | SDK Django (auth, middleware, RBAC, documents, intelligence) |
| [ncr-infra](https://github.com/NextCoreRevolutionCorp/ncr-infra) | Docker Compose + Dockerfile templates |
| [ncr-devkit](https://github.com/NextCoreRevolutionCorp/ncr-devkit) | CLI para scaffoldear nuevos proyectos |

### Proyectos cliente

| Repo | Stack | Fuente original |
|---|---|---|
| [saas-frontend](https://github.com/NextCoreRevolutionCorp/saas-frontend) | React + Vite + TanStack Query | portal-saas-ncr/frontend |
| [saas-backend](https://github.com/NextCoreRevolutionCorp/saas-backend) | Django 6 + DRF + pgvector | portal-saas-ncr/backend |
| [dirper-frontend](https://github.com/NextCoreRevolutionCorp/dirper-frontend) | React + Vite | portal-dirper/frontend |
| [dirper-backend](https://github.com/NextCoreRevolutionCorp/dirper-backend) | Django + DRF | portal-dirper/backend |
| [dagc-frontend](https://github.com/NextCoreRevolutionCorp/dagc-frontend) | React + Vite | dagc-frontend |
| [dagc-backend](https://github.com/NextCoreRevolutionCorp/dagc-backend) | Django + DRF | ⚠️ En progreso |

### Referencia (solo lectura)

| Repo | Descripción |
|---|---|
| [portal-saas-ncr](https://github.com/NextCoreRevolutionCorp/portal-saas-ncr) | Fuente original del proyecto SaaS |
| [portal-dirper](https://github.com/NextCoreRevolutionCorp/portal-dirper) | Fuente original del proyecto DIRPER/UdeC |

---

## Para developers: lee esto primero

👉 **[ncr-learning/CONTRIBUTING.md](https://github.com/NextCoreRevolutionCorp/ncr-learning/blob/main/CONTRIBUTING.md)** — guía completa de cómo migrar código.

### La regla más importante

```
NUNCA inventes código en los repos NCR.
Todo lo que agregues debe venir de un repo fuente real.
```

### Cómo empezar

```bash
# Clonar los repos que necesitas
git clone git@github.com:NextCoreRevolutionCorp/saas-backend.git
git clone git@github.com:NextCoreRevolutionCorp/saas-frontend.git

# Para agregar un componente a ncr-ui-kit
# 1. Verificar que existe en la fuente (portal-saas-ncr, portal-dirper, dagc-frontend)
# 2. Copiar (nunca mover)
# 3. Agregar al barrel export
# 4. Commit con mensaje que incluye la fuente
# → Ver CONTRIBUTING.md para el proceso completo
```

---

<div align="center">
  <sub>© 2026 NextCore Revolution Corp · Concepción, Chile</sub>
</div>
