#### 🚗 Taller Automitriz

**Sistema Integral de Gestión de Órdenes de Reparación y Flotas**

- **Descripción:** Plataforma empresarial diseñada para automatizar el ciclo de vida completo de un taller mecánico, desde la recepción del vehículo y la apertura de la hoja de trabajo digital, hasta la asignación de mecánicos, control de inventario de refacciones y facturación final.
- **Tech Stack:** .NET 8, ASP.NET Core Web API, EF Core, SQL Server, Clean Architecture, Repository Pattern, JWT.
- **Logros Técnicos:**
  - Diseño e implementación de una **Clean Architecture** (Domain, Application, Infrastructure, Web API) que aisló por completo las reglas de negocio de los proveedores de bases de datos y dependencias externas.
  - Optimización del módulo de asignación de órdenes de trabajo mediante consultas compiladas con **LINQ** y carga diferida controlada (_Eager Loading_), reduciendo el tiempo de respuesta del servidor en un 35% bajo alta demanda.
  - Modelado de una base de datos relacional robusta en **SQL Server** capaz de mantener de manera íntegra el histórico de reparaciones por número de chasis (VIN), asegurando auditorías rápidas del historial automotriz.

