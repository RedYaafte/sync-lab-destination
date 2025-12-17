# Test Sync Repo – Main 😸

Este es un repositorio de prueba para simular sincronización automática de archivos específicos hacia un segundo repositorio (`sync-lab-destination`).

## 🧪 Objetivo

Probar GitHub Actions que copie automáticamente ciertos archivos al repo secundario en cada push a `main`.

## 🔄 ¿Cómo funciona?

1. Se hace push a `main`.
2. GitHub Actions ejecuta el workflow `.github/workflows/sync.yml`.
3. Se hace commit y push automático al repo destino.

## 🧰 Requisitos

- Personal Access Token (PAT) con permisos de repo.
- Repositorio destino: `sync-lab-destination`
