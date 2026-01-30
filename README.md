# 📊 Sistema de Reportes de Daños a Infraestructura Pública

Este proyecto es una **plataforma web desarrollada con React y Firebase** que permite a los ciudadanos **reportar daños en infraestructura pública**, realizar seguimiento a sus reportes y facilitar la gestión por parte de entidades y administradores.

La aplicación está pensada para ser **responsive**, accesible desde dispositivos móviles y de escritorio, y cuenta con un **panel de estadísticas** que permite visualizar el estado y distribución de los reportes de forma clara y visual.

---

## 🧠 Objetivo del Proyecto

- Facilitar el reporte de daños en infraestructura pública
- Centralizar la información para entidades responsables
- Permitir seguimiento del estado de cada reporte
- Visualizar métricas y estadísticas en tiempo real
- Garantizar una buena experiencia de usuario en móvil y desktop

---

## 🚀 Tecnologías y Herramientas Utilizadas

### Frontend
- **React.js**
- **Material UI (MUI)** – diseño de componentes
- **React-Bootstrap** (en otras vistas del proyecto)
- **Recharts** – gráficos y estadísticas
- **Font Awesome** – iconografía
- **Responsive Design** (Mobile First)

### Backend / Servicios
- **Firebase**
  - Authentication (Email/Password y Google)
  - Firestore (Base de datos)
  - Storage (Imágenes de reportes)
  - Cloud Functions
- **Nodemailer** (envío de correos automáticos)

### Otros
- Control de roles (`admin`, `user`, `entidad`)
- Estados globales para optimización de consultas
- Buenas prácticas de arquitectura y componentes reutilizables

---

## 👥 Roles del Sistema

- **Usuario**
  - Crear reportes
  - Ver sus propios reportes
  - Eliminar reportes con confirmación
- **Entidad**
  - Recibir reportes asignados
  - Gestionar estados
- **Administrador**
  - Crear usuarios tipo entidad
  - Visualizar todos los reportes
  - Acceder al panel de estadísticas

---

## 📂 Estructura de Carpetas

```bash
src/
│
├── components/
│   ├── ReporteEstadisticas.jsx
│   ├── ReportModal.jsx
│   ├── Navbar.jsx
│   └── ...
│
├── pages/
│   ├── ReportPage.jsx
│   ├── MisReportes.jsx
│   ├── AdminSolicitudes.jsx
│   └── ...
│
├── context/
│   ├── AuthContext.jsx
│   ├── ReportesContext.jsx
│
├── services/
│   ├── firebase.js
│   ├── reportesService.js
│
├── assets/
│   ├── images/
│   └── icons/
│
└── App.jsx


---

## ✨ Tip pro (opcional, queda brutal en GitHub)

Si quieres que destaque más visualmente:

```md
> 🖼️ **Capturas del proyecto**  
> La carpeta `screenshots/` contiene imágenes del proceso de desarrollo, estructura del proyecto  
> y vistas finales en versión **desktop y mobile**.

