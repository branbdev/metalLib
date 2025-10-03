MetalEncyclopedia.sln
  ├── src/
  │   ├── Encyclopedia.Api         (ASP.NET Core Web API, controllers, GraphQL, auth)
  │   ├── Encyclopedia.Core        (domain models, interfaces, DTOs, exceptions)
  │   ├── Encyclopedia.Data        (EF Core, Postgres, repositories implementation)
  │   ├── Encyclopedia.Services    (business logic, validation, external services)
  │   └── Encyclopedia.Client      (frontend application if applicable)
  │
  ├── tests/
  │   ├── Encyclopedia.Api.Tests
  │   ├── Encyclopedia.Core.Tests
  │   ├── Encyclopedia.Data.Tests
  │   └── Encyclopedia.Services.Tests
  │
  └── tools/                       (migration scripts, data loaders, utilities)

   Encyclopedia.Core/
     ├── Models/            (Band, Album, Song, Artist, Review)
     ├── Interfaces/        (IRepository interfaces)
     ├── DTOs/              (Data Transfer Objects)
     ├── Enums/             (GenreType, CountryCode, etc.)
     └── Exceptions/        (Custom domain exceptions)

      Encyclopedia.Services/
     ├── BandServices/       (Band-related business logic)
     ├── AlbumServices/      (Album-related business logic)
     ├── SearchServices/     (Advanced search functionality)
     ├── UserServices/       (User management, permissions)
     ├── ValidationServices/ (Input validation)
     └── ExternalServices/   (Third-party integrations)