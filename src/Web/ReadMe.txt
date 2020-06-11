Application Core types
* Entities (business model classes that are persisted)
* Interfaces
* Services
* DTOs

Infrastructure types
* EF Core types (DbContext, Migration)
* Data access implementation types (Repositories)
* Infrastructure-specific services (for example, FileLogger or SmtpNotifier)

UI layer types
* Controllers
* Filters
* Views
* ViewModels
* Startup
https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures

Packages

Application Core

Infrastructure
Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore
Install-Package Microsoft.AspNetCore.Identity


UI Layer
