# movie-analyst-api
ui for the movie analyst website....im totally not ripping this off.......

# 🌱 DevOps Project - Estrategia de ramas (Git Flow)

Este proyecto sigue la estrategia de ramas **Git Flow** para garantizar un flujo de trabajo limpio, organizado y controlado durante el desarrollo y despliegue.

## 📌 Estructura de ramas

- `main`: Código estable en producción.
- `develop`: Rama principal de desarrollo.
- `feature/*`: Desarrollo de nuevas funcionalidades.
- `bugfix/*`: Correcciones de errores en desarrollo.
- `hotfix/*`: Correcciones críticas directamente en producción.
- `release/*`: Preparación de una nueva versión.
- `chore/*`: Cambios menores (infraestructura, documentación, CI/CD).

## 🛠️ Reglas para trabajar con ramas

1. **Nunca se desarrolla directamente en `main` ni `develop`.**
2. **Todas las nuevas funcionalidades parten de `develop`.**
3. **Commits con convención clara:**


## 🧪 Ejemplos

```bash
# Crear una nueva funcionalidad
git checkout develop
git checkout -b feature/dockerization

# Crear una corrección
git checkout -b bugfix/dockerfile-path

# Subir una tarea de infraestructura
git checkout -b chore/add-chef-recipes

/api           → Backend (NodeJS + TSQL)
/ui            → Frontend (HTML + JS)
/infra         → Scripts de Docker, Chef, Terraform, etc.
/ci-cd         → Jenkins, Spinnaker, Octopus
/docs          → Documentación adicional
README.md      → Estrategia de trabajo y generalidades
CHANGELOG.md   → Registro de cambios