# Blazor DataGrid - Set Instance for Child Component

A sample Blazor application demonstrating how to access and manipulate child grid instances in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component using master-detail grids with template-based hierarchical data.

## Overview

This repository demonstrates a practical pattern for working with master-detail grids in Blazor DataGrid. The example shows how to:

- Create master-detail grid layouts using `DetailTemplate`
- Store and access child grid instances dynamically via a dictionary
- Interact with child grids programmatically from parent grid events
- Handle toolbar interactions on child grids

The sample displays a master grid of employees with expandable detail rows showing order information for each employee. When a detail row is expanded, a child grid instance is created and can be accessed for operations like retrieving selected records.

## Features

- **Master-Detail Hierarchy** - Expandable rows that display related data in nested grids
- **Child Grid Instance Access** - Programmatic access to child grid instances for dynamic interactions
- **Dynamic Query Filtering** - Automatically filter detail grid data based on parent row selection
- **Toolbar Interactions** - Custom toolbar actions on child grids with event handling
- **Bulk Operations** - Retrieve and manipulate selected records from child grids asynchronously
- **Efficient Pagination** - Handle large datasets with configurable page sizes on detail grids

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-set-instance-for-child-component.git
cd blazor-datagrid-set-instance-for-child-component
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

**Documentation**: https://blazor.syncfusion.com/documentation/getting-started/blazor-server-side-visual-studio

**Online example**: https://blazor.syncfusion.com/demos/datagrid/overview?theme=fluent2