# Creating Blazor Live Chart

## Overview

This sample demonstrates how to create a live chart using the Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts) component. The application renders a Blazor Line Chart and continuously updates the displayed data to simulate a real-time visualization scenario. This approach is useful when representing frequently changing values such as monitoring data, live measurements, operational metrics, or continuously refreshed datasets.

The project is implemented as a Blazor application and showcases a live-updating chart experience using the Syncfusion charting components.

## Key Features

- Demonstrates creating a live chart using the Syncfusion Blazor Line Chart component.
- Shows continuous chart updates as data changes over time.
- Uses a dedicated Blazor project (`LiveChart.csproj`) to render the chart.
- Illustrates real-time visualization techniques using a line-series chart representation.
- Provides a reference implementation for scenarios requiring continuously refreshed chart data.
- Demonstrates chart rendering within a standard Blazor application structure.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `LiveChart.sln`.
3. Restore all NuGet packages.
4. Set the LiveChart project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root containing `LiveChart.csproj`.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Blazor page that renders the Syncfusion live chart sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see https://help.syncfusion.com/chart-sdk/blazor/charts/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
