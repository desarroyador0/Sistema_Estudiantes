# Sistema Estudiantes - Primera Etapa

Base funcional construida con React + Vite, orientada a gestion academica personal (notas, tareas, pomodoro, finanzas y habitos).

## Requisitos

- Node.js 18+
- npm 9+

## Ejecutar en desarrollo

```bash
npm install
npm run dev
```

## Build de produccion

```bash
npm run build
npm run preview
```

## Estructura

- `index.html`: plantilla HTML raiz de Vite.
- `src/main.jsx`: punto de entrada React.
- `src/App.jsx`: aplicacion principal StudyFlow.
- `vite.config.js`: configuracion de Vite.

## Estado de primera etapa

- Navegacion por modulos: Inicio, Academico, Tareas, Pomodoro, Finanzas y Habitos.
- Alta y gestion local de datos en cada modulo.
- Persistencia en `localStorage` para no perder datos al recargar.
- Build de produccion validado con `vite build`.

## Siguiente etapa sugerida

1. Separar `src/App.jsx` en modulos (`components`, `features`, `hooks`).
2. Reemplazar `localStorage` por backend/API (auth, usuarios y sincronizacion).
3. Agregar pruebas de componentes y logica de negocio.
4. Implementar code-splitting por secciones para reducir bundle inicial.
