# Getting Started with the Syncfusion Blazor Badge Component

## Overview

This sample demonstrates how to display notification badges within a Syncfusion [Blazor Badge](https://www.syncfusion.com/blazor-components/blazor-badge) implementation integrated with a Syncfusionn uses badge elements to indicate notification counts for messages, user profiles, and favorite items. It showcases badge positioning, notification styling, color variants, and toolbar template integration to create a practical notification center experience in a Blazor application.

## Key Features

- Integrates badge notifications within a Syncfusion `SfToolbar` component using `ToolbarItem` templates.
- Uses `e-badge-notification` to display notification counts on toolbar actions.
- Demonstrates badge overlay positioning with the `e-badge-overlap` CSS class.
- Showcases multiple badge styles using `e-badge-primary`, `e-badge-success`, and `e-badge-info`.
- Displays notification counters for messages, user profiles, and favorites using badge content values.
- Uses `ItemAlign.Left` and `ItemAlign.Right` to organize toolbar content and notification indicators.
- Includes custom SVG-based icons rendered through CSS background images.
- Implements responsive toolbar behavior with CSS media queries for smaller screen sizes.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone this repository.
2. Open the repository folder in Visual Studio 2022.
3. Restore NuGet packages.
4. Set the Blazor WebAssembly project as the startup project if required.
5. Build the project.
6. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/Index.razor` — Main sample page demonstrating notification badges integrated within a Syncfusion Toolbar.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/badge/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.