# Museum .NET Application

Educational client-server museum application developed with .NET 8.

The project consists of a WPF desktop client and an ASP.NET Core REST API used to work with museum artworks and application users.

## Features

- Desktop user interface
- Museum artwork catalogue
- User data management
- Client-server architecture
- REST API
- CRUD operations
- Database persistence
- Swagger API documentation
- Entity Framework Core migrations

## Tech Stack

### Backend

- C#
- .NET 8
- ASP.NET Core Web API
- Entity Framework Core
- SQLite
- Swagger / Swashbuckle

### Desktop Client

- WPF
- XAML
- Material Design
- Prism
- ReactiveUI
- MVVM


## Backend Setup

Open:

backend/SiteAPI/SiteAPI.sln

Restore NuGet packages.

Apply Entity Framework migrations:

Update-Database

Run the ASP.NET Core application.

Swagger UI can then be used to inspect and test the REST API.

## Frontend Setup

Open:

frontend/TheMuseum.sln

Build and run the WPF application using Visual Studio.

## Purpose

The project was developed as a university course project to practice:

- ASP.NET Core
- Entity Framework Core
- REST API design
- WPF
- MVVM
- client-server architecture
- relational database design

## Status

Educational project.
