<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0d2026,100:00f7a7&height=180&section=header&text=Portafolio%20de%20Proyectos&fontSize=42&fontColor=ffffff&fontAlignY=50&animation=fadeIn" width="100%" />

[![Volver al Perfil](https://img.shields.io/badge/←_Volver_al_Perfil_Principal-0d1117?style=for-the-badge&logo=github&logoColor=00f7a7)](./README.md)
&nbsp;
[![Contactar](https://img.shields.io/badge/Contactar_por_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/584167071715)

</div>

---

## 📡 01 — API RESTful .NET Core + Swagger + JWT

> **Arquitectura robusta, documentación interactiva y pruebas de integración automatizadas**

<p>
  <img src="https://img.shields.io/badge/.NET_Core_7-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger_/_OpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/JWT_Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
</p>

### 🎯 Descripción General
Servicio backend de nivel empresarial estructurado bajo principios de Clean Architecture y Repository Pattern. Ofrece endpoints completamente protegidos y documentados en tiempo real mediante Swagger UI, facilitando el consumo por parte de clientes frontend y aplicaciones móviles.

### ✨ Aspectos Clave
- **Documentación Viva:** Generación automática de especificaciones OpenAPI 3.0 mediante Swagger con soporte para envío directo de tokens Bearer.
- **Seguridad Robusta:** Autenticación y control de acceso basado en roles (RBAC) con JSON Web Tokens (JWT).
- **Acceso a Datos Eficiente:** Consultas optimizadas con Entity Framework Core, migraciones automáticas y transacciones atómicas.
- **Manejo Centralizado de Excepciones:** Middleware personalizado para capturar errores y retornar respuestas estandarizadas JSON (`ProblemDetails`).
- **Pruebas Automatizadas:** Suite de tests unitarios con xUnit asegurando cobertura en controladores y servicios de dominio.

| Capa / Módulo | Tecnología Implementada |
| :--- | :--- |
| **Framework** | .NET Core 7 / C# |
| **Especificación API** | OpenAPI 3.0 / Swagger UI |
| **Seguridad** | ASP.NET Identity + JWT Bearer Tokens |
| **Persistencia** | Entity Framework Core (Code-First) |
| **Testing** | xUnit + FluentAssertions + Moq |

[📂 Explorar Repositorio en GitHub](https://github.com/jeffersonm-dev/api-dotnet-swagger)

---

## 🖥️ 02 — Aplicación Full Stack Vue.js 3 + SQL Server

> **Single Page Application reactiva conectada a backend .NET Core y base de datos relacional**

<p>
  <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Vuex_/_Pinia-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" />
</p>

### 🎯 Descripción General
Plataforma web moderna que combina una interfaz de usuario interactiva y fluida construida con Vue.js 3 (Composition API) con un backend desacoplado en .NET Core y persistencia en Microsoft SQL Server.

### ✨ Aspectos Clave
- **Frontend SPA Reactivo:** Componentes modulares y reutilizables utilizando Vue 3 y Vue Router para navegación fluida sin recargas.
- **Gestión de Estado Centralizada:** Manejo reactivo de estado global garantizando sincronización en tiempo real entre componentes.
- **Comunicación HTTP Asíncrona:** Integración de cliente Axios con interceptores para inyección automática de tokens de autenticación y manejo de errores.
- **Optimización de Consultas:** Procedimientos almacenados e índices en SQL Server para tiempos de respuesta ultra rápidos.
- **UI/UX Adaptativa:** Interfaz adaptable a móviles, tablets y escritorios con diseño moderno.

| Capa / Módulo | Tecnología Implementada |
| :--- | :--- |
| **Frontend** | Vue.js 3 + Vite + Composition API |
| **Estado Global** | Pinia / Vuex |
| **Backend REST** | ASP.NET Core Web API |
| **Base de Datos** | Microsoft SQL Server |
| **Estilos** | CSS3 Modular / Modern Responsive Design |

[📂 Explorar Repositorio en GitHub](https://github.com/jeffersonm-dev/vue-sql-app)

---

## 🗄️ 03 — Gestor de Base de Datos Multi-Motor

> **Diseño de esquemas, procedimientos almacenados y optimización en PostgreSQL & MySQL**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL_8-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Dapper-00599C?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" />
</p>

### 🎯 Descripción General
Arquitectura de persistencia multi-motor diseñada para escenarios que demandan alta concurrencia, integridad transaccional y optimización de consultas complejas.

### ✨ Aspectos Clave
- **Multi-RDBMS:** Soporte simultáneo para PostgreSQL y MySQL con abstracción de persistencia mediante micro-ORM Dapper.
- **Lógica en el Motor:** Implementación de funciones, triggers y stored procedures para operaciones críticas con mínima sobrecarga de red.
- **Estrategias de Indexación:** Índices B-Tree y compuestos diseñados para reducir tiempos de ejecución en consultas analíticas.
- **Seguridad & Normalización:** Modelado 3NF garantizando cero redundancia y consistencia estricta de datos.

| Capa / Módulo | Tecnología Implementada |
| :--- | :--- |
| **Motores** | PostgreSQL 15, MySQL 8, SQL Server |
| **Micro-ORM** | Dapper (.NET Core) |
| **Lógica de Persistencia** | Stored Procedures, Views, Triggers |
| **Optimización** | Planes de ejecución (EXPLAIN ANALYZE) |

[📂 Explorar Repositorio en GitHub](https://github.com/jeffersonm-dev/database-management)

---

## 🧪 04 — Suite de Testing Automatizado & QA

> **Ecosistema integral de aseguramiento de calidad: unitario, integración y validación de contratos**

<p>
  <img src="https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger_UI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub_Actions_CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

### 🎯 Descripción General
Ecosistema de pruebas continuas diseñado para validar la integridad de APIs críticas desde el código fuente hasta el entorno de ejecución, reduciendo la regresión de software a cero.

### ✨ Aspectos Clave
- **Pruebas Unitarias Aisladas:** Implementación de tests con xUnit utilizando dobles de prueba (Moq) para aislar la lógica de negocio.
- **Colecciones de Pruebas en Postman:** Scripts automatizados en JavaScript para validar esquemas JSON, códigos de respuesta y tiempos de latencia.
- **Validación de Contratos:** Comprobación estricta de esquemas OpenAPI para asegurar compatibilidad continua con clientes externos.
- **CI/CD Integrado:** Ejecución automática de pruebas ante cada `push` o `pull request` en GitHub Actions.

| Herramienta | Función en el Ecosistema |
| :--- | :--- |
| **xUnit** | Pruebas unitarias de servicios y controladores |
| **Moq** | Mocking de dependencias y repositorios de datos |
| **Postman** | Pruebas de integración, variables de entorno y regresión |
| **Newman / CI** | Ejecución de colecciones Postman en pipelines CI/CD |

[📂 Explorar Repositorio en GitHub](https://github.com/jeffersonm-dev/testing-suite)

---

<div align="center">

[![Volver al Perfil](https://img.shields.io/badge/←_Volver_al_Perfil_Principal-0d1117?style=for-the-badge&logo=github&logoColor=00f7a7)](./README.md)
&nbsp;
[![Contactar](https://img.shields.io/badge/¿Tienes_un_proyecto?_¡Hablemos!-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/584167071715)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f7a7,50:0d2026,100:090d16&height=100&section=footer&animation=fadeIn" width="100%" />

</div>
