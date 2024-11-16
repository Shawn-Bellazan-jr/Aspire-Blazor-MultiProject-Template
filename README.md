# Aspire Blazor Multi-Project Template

A complete .NET Aspire 9.0 template designed for distributed applications, featuring:

- **Blazor WebAssembly Frontend**: Modern single-page application built with Razor components.
- **Management API with Redis**: API layer backed by Redis for state management.
- **Semantic Kernel AI Service**: Integrated AI capabilities for advanced workflows.
- **Shared Utilities**: Reusable models and utility classes for cross-project functionality.
- **Testing Support**: Pre-configured MSTest project for unit testing.

## Features
- **Multi-Project Architecture**: Each layer of the application is modularized for scalability and maintainability.
- **Built-in Redis Integration**: Configured with StackExchange.Redis for efficient caching and messaging.
- **Semantic Kernel Support**: Ready for advanced AI scenarios using Semantic Kernel.
- **Customizable Template**: Easily adapt the project structure to suit your specific needs.

## How to Use

### Install the Template
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Aspire-Blazor-MultiProject-Template.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd Aspire-Blazor-MultiProject-Template
   ```
3. Install the template:
   ```bash
   dotnet new install .
   ```

### Generate a New Project
Create a new project using the installed template:
```bash
dotnet new aspire-multi --name MyAspireApp
```

### Open in Visual Studio
1. Open the solution file:
   ```bash
   MyAspireApp/MyAspireApp.sln
   ```
2. Build and run the project from Visual Studio.

## Folder Structure
```plaintext
src/
??? MyAspireApp.AppHost/                # Application entry point
??? MyAspireApp.ManagementService/      # Redis-backed management API
??? MyAspireApp.BlazorFrontend/         # Blazor WebAssembly app
??? MyAspireApp.SemanticKernelService/  # AI integration with Semantic Kernel
??? MyAspireApp.Shared/                 # Shared models and utilities
test/
??? MyAspireApp.Tests/                  # Unit tests
```

## Prerequisites
- .NET SDK 7.0 or later
- Redis (local or cloud-hosted)
- Visual Studio 2022 (optional, for IDE support)

## License
This repository is licensed under the [MIT License](LICENSE).
