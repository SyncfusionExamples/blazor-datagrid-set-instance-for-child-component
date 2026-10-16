# Blazor DataGrid - Set Instance for Child Component

## Overview

This sample demonstrates how to get and set a child grid instance in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). When working with hierarchical DataGrid layouts, developers often need to access child grid instances programmatically to perform operations, update settings, or interact with nested grid content. The sample illustrates a practical implementation pattern for obtaining references to child DataGrid components and managing them within a hierarchy grid structure. This approach is useful when implementing advanced parent-child grid interactions and dynamic grid behavior.

## Key Features

- Demonstrates hierarchical DataGrid implementation using Syncfusion Blazor DataGrid.
- Shows how to obtain a reference to a child grid instance.
- Demonstrates assigning and managing child grid instances programmatically.
- Provides a reference implementation for parent-child DataGrid interaction scenarios.
- Illustrates communication between parent and child DataGrid components.
- Enables developers to access child grid APIs after the grid has been rendered.
- Demonstrates instance management techniques used in hierarchy grid applications.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file located in the `ChildGridInstance` project folder.
3. Restore all NuGet packages.
4. Set the `ChildGridInstance` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
cd ChildGridInstance
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `ChildGridInstance/Pages/` — contains the Blazor page that hosts the parent DataGrid, child DataGrid, and child instance management implementation.
- `ChildGridInstance/Data/` — contains the sample data used by the hierarchy grid.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Hierarchy Grid documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/detail-template

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
