# Blazor DataGrid - Display Validation Message in Dialog Template

## Overview

This sample demonstrates how to display validation messages in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) add and edit dialog when a model property participates in validation but is not explicitly defined as a GridColumn. In dialog template editing scenarios, developers often include custom form fields or hidden model properties that require validation. This sample shows how validation feedback is surfaced within the dialog interface so users can correct invalid input before completing Create, Update, or Edit operations.

## Key Features

- Demonstrates validation handling within the Syncfusion Blazor DataGrid dialog editing workflow.
- Shows how validation messages are displayed when a model field is not represented as a GridColumn definition.
- Uses DataGrid add and edit dialogs to capture user input.
- Demonstrates model-based validation during CRUD operations.
- Provides a reference implementation for dialog template validation scenarios.
- Illustrates how validation feedback can be displayed for custom dialog fields outside the standard grid column configuration.
- Helps developers maintain consistent validation behavior across visible and non-visible data fields.
- Focuses specifically on validation message rendering during dialog-based editing operations.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `DisplayValidationMessage.sln`.
3. Restore all NuGet packages.
4. Set the appropriate startup project (`DisplayValidationMessage` or `DisplayValidationMessage.Client`) based on the framework version being tested.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the appropriate project folder.

```bash
cd DisplayValidationMessage
dotnet restore
dotnet run
```

or

```bash
cd DisplayValidationMessage.Client
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `DisplayValidationMessage/` — contains the primary Blazor implementation used to demonstrate DataGrid dialog validation behavior.
- `DisplayValidationMessage.Client/` — contains the client-side implementation of the validation sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Data Annotation and Validation documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/data-annotation

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
