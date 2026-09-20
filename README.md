# Full-Stack Web System with Clean Architecture, REST API and Generative AI Integration - .NET 10
Academic project developed individually for the 'Web Development assisted by AI' course at Universidad ORT Uruguay (2026).  A full-stack astronomical observatory management system built with Clean Architecture and Domain-Driven Design, integrating Google Gemini AI for equipment suitability evaluation

## Tech Stack
- **Backend:** C# / .NET 10 / ASP.NET Core Web API
- **Frontend:** ASP.NET Core MVC
- **ORM:** Entity Framework Core 10
- **Database:** SQL Server
- **AI Integration:** Google Gemini 2.5 Flash API
- **Auth:** Argon2id password hashing
- **Deployment:** SOMEE (API live at http://www.observatorio-api.somee.com/swagger)

## Architecture
Clean Architecture with DDD across two separate solutions:
- `SolucionObservatorio/` — Web API + business logic layers
- `SolucionObservatorioMVC/` — Independent MVC client

## Features
- Equipment management (telescopes, mounts, cameras, oculars)
- Loan and return workflow with automatic audit logging
- AI-powered observation validation via Google Gemini
- Celestial object ranking by observation count
- Role-based access (Administrator, Coordinator, Member)
