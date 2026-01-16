---
name: "Web App Builder"
description: "Genera aplicaciones web completas con React, Tailwind y componentes reutilizables. Para landings, dashboards, apps SAAS."
category: "Development"
author: "Agency"
version: "1.0"
tags: ["react", "web", "fullstack", "tailwind", "apps"]
---

# Web App Builder

## When to use
- Necesitas una landing page React moderna
- Quieres un dashboard o panel de control
- Necesitas una app web completa (SAAS)
- Clientes: legales, automotriz, cocinas, servicios

## Instructions

1. **Define especificaciones:**
   - Tipo: landing | dashboard | app
   - Páginas/secciones necesarias
   - Funcionalidades clave
   - Datos: estáticos o API
   - Autenticación: sí/no

2. **Estructura generada:**
   ```
   src/
   ├── components/     (reutilizables)
   ├── pages/          (vías)
   ├── hooks/          (lógica custom)
   ├── context/        (estado global)
   ├── styles/         (Tailwind)
   └── App.tsx
   ```

3. **Tecnología:**
   - React 18 + TypeScript
   - Tailwind CSS 3.4
   - shadcn/ui para componentes
   - React Router para navegación
   - Axios para API calls

4. **Entrega:**
   - Artifact autocóntenido (HTML)
   - Componentes listos para producir
   - Responsive (mobile-first)

## Examples

### Landing Page Abogados
```
Secciones:
- Hero (titular + CTA "Consulta Gratis")
- Áreas de práctica (3 tarjetas)
- Casos de éxito (slider)
- Testimonios
- Formulario contacto
- Footer
```

### Dashboard Parque Automotriz
```
Funciones:
- Listar vehículos (tabla + filtros)
- Ver detalles (modal/página)
- Agregar vehículo (form)
- Reportes (gráficos básicos)
- Exportar CSV
```

## Workflow
1. Usuario describe necesidad
2. Claude genera boilerplate React
3. Incluye componentes + estilos Tailwind
4. Agrupa en single HTML (artifact)
5. Usuario lo copia a Vercel/hosting

## Stack
- Frontend: React + TypeScript + Tailwind
- Componentes: shadcn/ui (30+ listos)
- Deploy: Vercel, Netlify, o tu hosting
- API: Fetch + Axios
- Auth: JWT o Auth0 (opcional)

## Output
- Single .html artifact
- Componentes copiables (.tsx)
- README con instrucciones
- Package.json preconfigurado

---

**Uso:** Pide una app web describiendo el tipo, páginas y funciones.
