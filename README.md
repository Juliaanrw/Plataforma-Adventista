# Plataforma Adventista - Sistema de Gestión Integral

Sistema web desarrollado para la **Iglesia Adventista del Séptimo Día de Tirrases**, diseñado para centralizar la administración de miembros, visitantes, asistencias, seguimientos pastorales, estudios bíblicos y actividades de la congregación.

## Stack Tecnológico e Infraestructura
* **Frontend:** ASP.NET Core MVC + Razor + Bootstrap + JavaScript
* **Backend:** C# + ASP.NET Core (Services / Lógica de Negocio)
* **Base de Datos Relacional:** PostgreSQL (Alojado en Supabase Cloud)
* **Acceso a Datos (ORM):** Entity Framework Core (con conector `Npgsql`)
* **Autenticación y Seguridad:** Supabase Auth (JWT) / ASP.NET Core Identity
* **Control de Versiones:** Git + GitHub
* **Despliegue / Hosting:** Supabase Cloud (Datos) + Render / Azure (Backend)

## Equipo de Desarrollo (Universidad Fidélitas)
* **Emily Mora Matarrita** — Coordinadora del proyecto y Analista de Requerimientos
* **Julián Edgardo Rodríguez Espinoza** — Desarrollador Frontend, Pruebas y DBA (PostgreSQL/Supabase)
* **Víctor Josué Céspedes Moya** — Encargado de Base de Datos e Integración
* **Joseth Céspedes Moya** — Desarrollador Backend (C# / .NET)

## Módulos Principales del Sistema
1. **Seguridad y Accesos:** Inicio de sesión seguro, gestión de usuarios y roles diferenciados (Dirigente vs. Miembro).
2. **Directorio y Expedientes:** Expediente unificado de miembros, visitantes e interesados con historial completo.
3. **Control Operativo:** Registro de asistencia a cultos y actividades, control de ausencias y alertas automáticas.
4. **Seguimiento Pastoral:** Gestión de contactos, pendientes y reintentos para visitas y llamadas.
5. **Formación y Eventos:** Control de estudios bíblicos activos, calendario de la iglesia, anuncios y portal de consulta para miembros.
6. **Módulos Innovadores:** Recordatorios de citas pastorales, agenda inteligente con detección de conflictos de recursos y análisis estadístico de ausencias.

---
*Desarrollado en el marco de los cursos de ingeniería de software de la Universidad Fidélitas (2026-2027).*
