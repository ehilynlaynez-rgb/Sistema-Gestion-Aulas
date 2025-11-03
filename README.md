# Sistema de Gestión de Aulas · Intecap (Final)

Este repo incluye dos formas de uso:

## 1) **GitHub Pages (Demo estática)** — listo para subir
- Carpeta: `frontend/gh-pages`
- No requiere backend. Simula datos con `data.json` y guarda registro de usuarios en `localStorage`.
- Ideal para **presentación** pública (opción que elegiste).

## 2) **Modo completo con Access + Node**
- Carpeta: `backend/`, `data/`, `scripts/`.
- Ejecuta `./scripts/CreateAccessDb.ps1` (Windows) para crear `data/aulas.accdb` con tus datos.
- Inicia backend: `cd backend && npm install && npm start` (http://localhost:3001)
- Cambia `API_BASE` en `frontend/app/script.js` si usas el front completo (opcional).

### Paleta Intecap
- Azul: #0033A0
- Acento amarillo: #FFC423
- Azul claro UI: #2E79B9
- Fondos: blanco / gris claro #F3F4F6

Autor mostrado en UI: **Administración Aulas**
