# Blazor DataForm CRUD Actions

A demonstration application showcasing CRUD (Create, Read, Update, Delete) operations using the [ Blazor DataForm](https://blazor.syncfusion.com/documentation/dataform/getting-started/) component in a Blazor Server-side application. This project provides an intuitive interface for managing employee records with built-in validation, modal dialogs, and responsive design.

## Features

- **Create** new employee records through an integrated form dialog
- **Read** and display employee data in a sortable table
- **Update** existing records with inline editing capabilities
- **Delete** records with confirmation support
- Built-in form validation using data annotations
- Modal dialog interface for add/edit operations
- Responsive Bootstrap-based UI

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository ###
   ```bash
   git clone https://github.com/SyncfusionExamples/blazor-data-form-crud-actions.git
   cd blazor-data-form-crud-actions
   ```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## Key Components

### EmployeeDetails

The `EmployeeDetails` class defines the employee entity with validation attributes:

- `Id` - Auto-generated employee identifier
- `Name` - Employee full name (required)
- `DateOfBirth` - Birth date (required)
- `Designation` - Job title (required)
- `Salary` - Compensation amount (required)

### DataForm Integration

The application uses `SfDataForm` with `EditContext` and `DataAnnotationsValidator` for client-side validation, demonstrating how Syncfusion's DataForm component integrates with Blazor's built-in validation system.

## See Also

- [Blazor Forms & Validation Guide](https://www.learnblazor.com/form-validation)
- [Blazor Community Forum](https://www.syncfusion.com/forums/blazor)
