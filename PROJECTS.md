<div align="center">

<img src="./assets/header.svg" width="100%" alt="Jefferson Martinez - Proyectos" />

<br/><br/>

<a href="./README.md">
  <img src="https://img.shields.io/badge/←_Volver_al_Perfil_Principal-0d1117?style=flat-square&logo=github&logoColor=00f7a7" alt="Volver" />
</a>
&nbsp;
<a href="https://wa.me/584145572936?text=Hola%20Jefferson,%20vi%20tu%20proyecto%20en%20GitHub%20y%20me%20gustar%C3%ADa%20conversar">
  <img src="https://img.shields.io/badge/WhatsApp-+58_414--5572936-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" />
</a>
&nbsp;
<a href="mailto:jefferson.martinez.dev@gmail.com">
  <img src="https://img.shields.io/badge/Email-jefferson.martinez.dev%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>

---

## 📡 01 — API RESTful .NET Core + Swagger + JWT

> **Arquitectura robusta, documentación interactiva y pruebas de integración automatizadas**

<p>
  <img src="https://img.shields.io/badge/.NET_Core_7-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger_/_OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/JWT_Authentication-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
</p>

### 🎯 Descripción General
Servicio backend de nivel profesional estructurado bajo principios de Clean Architecture y Repository Pattern. Ofrece endpoints protegidos y documentados en tiempo real mediante Swagger UI, facilitando el consumo seguro y eficiente por parte de clientes web y móviles.

### ✨ Aspectos Clave
- **Documentación Interactiva:** Especificaciones OpenAPI 3.0 mediante Swagger con soporte para envío directo de tokens Bearer.
- **Seguridad Robusta:** Autenticación y control de acceso basado en roles (RBAC) con JSON Web Tokens (JWT).
- **Acceso a Datos Eficiente:** Consultas optimizadas con Entity Framework Core, migraciones automáticas y transacciones.
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
  <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=flat-square&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Vuex_/_Pinia-4FC08D?style=flat-square&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white" />
</p>

### 🎯 Descripción General
Plataforma web moderna que combina una interfaz de usuario interactiva y fluida construida con Vue.js 3 (Composition API) con un backend desacoplado en .NET Core y persistencia en Microsoft SQL Server.

### ✨ Aspectos Clave
- **Frontend SPA Reactivo:** Componentes modulares y reutilizables utilizando Vue 3 y Vue Router para navegación fluida.
- **Gestión de Estado Centralizada:** Manejo reactivo de estado global garantizando sincronización en tiempo real entre componentes.
- **Comunicación HTTP Asíncrona:** Integración de cliente Axios con interceptores para inyección automática de tokens de autenticación y manejo de errores.
- **Optimización de Consultas:** Procedimientos almacenados e índices en SQL Server para tiempos de respuesta ultra rápidos.

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
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Dapper-00599C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white" />
</p>

### 🎯 Descripción General
Arquitectura de persistencia multi-motor diseñada para escenarios que demandan alta concurrencia, integridad transaccional y optimización de consultas complejas.

### ✨ Aspectos Clave
- **Multi-RDBMS:** Soporte simultáneo para PostgreSQL y MySQL con abstracción de persistencia mediante micro-ORM Dapper.
- **Lógica en el Motor:** Implementación de funciones, triggers y stored procedures para operaciones críticas con mínima sobrecarga de red.
- **Estrategias de Indexación:** Índices B-Tree y compuestos diseñados para reducir tiempos de ejecución en consultas analíticas.

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
  <img src="https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger_UI-85EA2D?style=flat-square&logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub_Actions_CI-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

### 🎯 Descripción General
Ecosistema de pruebas continuas diseñado para validar la integridad de APIs críticas desde el código fuente hasta el entorno de ejecución, reduciendo la regresión de software a cero.

### ✨ Aspectos Clave
- **Pruebas Unitarias Aisladas:** Implementación de tests con xUnit utilizando dobles de prueba (Moq) para aislar la lógica de negocio.
- **Colecciones de Pruebas en Postman:** Scripts automatizados en JavaScript para validar esquemas JSON, códigos de respuesta y tiempos de latencia.
- **Validación de Contratos:** Comprobación estricta de esquemas OpenAPI para asegurar compatibilidad continua con clientes externos.

| Herramienta | Función en el Ecosistema |
| :--- | :--- |
| **xUnit** | Pruebas unitarias de servicios y controladores |
| **Moq** | Mocking de dependencias y repositorios de datos |
| **Postman** | Pruebas de integración, variables de entorno y regresión |
| **Newman / CI** | Ejecución de colecciones Postman en pipelines CI/CD |

[📂 Explorar Repositorio en GitHub](https://github.com/jeffersonm-dev/testing-suite)

---

<div align="center">

<a href="./README.md">
  <img src="https://img.shields.io/badge/←_Volver_al_Perfil_Principal-0d1117?style=flat-square&logo=github&logoColor=00f7a7" alt="Volver" />
</a>
&nbsp;
<a href="https://wa.me/584145572936?text=Hola%20Jefferson,%20vi%20tu%20proyecto%20en%20GitHub%20y%20me%20gustar%C3%ADa%20conversar">
  <img src="https://img.shields.io/badge/WhatsApp-+58_414--5572936-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="Contactar" />
</a>
&nbsp;
<a href="mailto:jefferson.martinez.dev@gmail.com">
  <img src="https://img.shields.io/badge/Email-jefferson.martinez.dev%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
</a>

<br/><br/>

<img src="./assets/footer.svg" width="100%" alt="Footer" />

</div>
