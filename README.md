# Blazor Server DataGrid — EditTemplate with TimePicker

A sample Blazor Server application demonstrating how to render the [Blazor TimePicker](https://www.syncfusion.com/blazor-components/blazor-timepicker) component within a [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) EditTemplate for inline time editing with automatic data synchronization.

## Overview

This project showcases seamless integration of the Blazor TimePicker component into a DataGrid's edit template. Users can edit time values directly in the grid with a user-friendly time picker interface, and changes are automatically reflected in the underlying data source.

## Features

- **TimePicker Edit Template** — Render inline time picker in DataGrid edit mode
- **Auto-Sync Data** — Changes automatically update the data source on save
- **Integrated Validation** — Built-in validation rules for required fields
- **AutoComplete Integration** — Custom edit templates for enhanced UX
- **Fast Performance** — Efficient rendering with Blazor DataGrid

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2-DataGrid-BlazorServer-GridEdit-EditTemplate-TimePicker.git
cd GridEditTemplateWithTimePicker
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

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/edit-types#render-timepicker-in-edittemplate

**Live Demo**: https://blazor.syncfusion.com/demos/datagrid/edit-types?theme=bootstrap5