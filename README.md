--> ENGLISH
# .NET CRUD API – Technical Test
Project developed as a technical test for a .NET Developer position. It consists of a basic RESTful API that enables CRUD operations for machines and components, using .NET, Entity Framework Core, the DTO pattern, and Swagger for endpoint documentation and testing.

The system persists information in a relational database, managing the data model through Entity Framework migrations. The main goal is to demonstrate best practices in API design, project structuring, and the efficient use of backend technologies such as C#, SQL Server, 
and automatic migrations.

When running the project, the Swagger UI opens automatically, allowing you to interactively test all endpoints and view the data schemas.

## Technologies used
- .NET 8
- Entity Framework Core
- SQL Server
- Swagger
- DTO pattern
- Database migrations

## Project structure
- Layered architecture (Controllers, Models, DTOs, Data)
- Controllers for main entities (machines and components)
- Database management with DbContext and migrations
- Endpoint documentation and testing with Swagger

## How to run the project
1. Clone the repository.
2. Restore NuGet packages.
3. Configure the database connection string in `appsettings.json`.
4. Run Entity Framework migrations to create the database schema.
5. Start the project.
6. The interactive documentation will be automatically available at `/swagger`.

## Swagger UI view
![image](https://github.com/user-attachments/assets/0711737f-a19d-4260-aa6c-6dad5d5773ca)

--->ESPAÑOL
# API CRUD .NET – Prueba Técnica
Proyecto desarrollado como prueba técnica para una posición de desarrollador .NET. Consiste en una API RESTful básica que permite operaciones CRUD sobre máquinas y componentes, utilizando .NET, Entity Framework Core, el patrón DTO y Swagger para la documentación -
y pruebas de los endpoints.

El sistema persiste la información en una base de datos relacional, gestionando el modelo de datos a través de migraciones de Entity Framework. El objetivo principal es demostrar buenas prácticas en el diseño de APIs, estructuración de proyectos y uso -
eficiente de tecnologías backend como C#, SQL Server y migraciones automáticas.

Al ejecutar el proyecto, se abre automáticamente la interfaz de Swagger, permitiendo probar todos los endpoints de forma interactiva y visualizar los esquemas de datos.

## Tecnologías utilizadas
- .NET 8
- Entity Framework Core
- SQL Server
- Swagger
- Patrón DTO
- Migraciones de base de datos

## Estructura del proyecto
- Separación por capas (Controllers, Models, DTOs, Data)
- Controladores para entidades principales (máquinas y componentes)
- Gestión de base de datos con DbContext y migraciones
- Documentación y pruebas de endpoints con Swagger

## Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. Restaurar los paquetes NuGet.
3. Configurar la cadena de conexión a la base de datos en `appsettings.json`.
4. Ejecutar las migraciones de Entity Framework para crear la base de datos.
5. Iniciar el proyecto.
6. La documentación interactiva estará disponible automáticamente en `/swagger`.

## Vista de Swagger
![image](https://github.com/user-attachments/assets/11875bfa-a55b-4b2d-b14e-75eed85f4039)

