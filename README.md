# Creating Blazor Live Chart

This repository contains a small Blazor sample that demonstrates how to create a live-updating line chart using a Blazor Line Chart component and a simple data service.

## Project Overview

The sample shows how to push real-time or periodic data into a Blazor line chart so the UI reflects live changes. It is intended as a minimal, focused demo for developers learning how to bind streaming or timed data updates to a chart component in a Blazor app.

## Features

- Live-updating line chart bound to a data source
- Simple data service for generating or supplying sample values
- Blazor Server/WebAssembly-friendly structure (sample uses .NET project files)

## Prerequisites

- Visual Studio 2022
- .NET 6 SDK (project targets net6.0)

## Installation & How to run

1. Clone or checkout this project to a location on your disk.
2. Open the solution file in Visual Studio 2022.
3. Restore NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Run the project from Visual Studio or run `dotnet run` from the project folder.

## Usage

Navigate to the sample page (e.g., the index or a demo page) to see the line chart update as the sample data service produces new values. The project includes a simple `WeatherForecastService`-style data provider which you can inspect and adapt.

## Troubleshooting & Support

- If packages fail to restore, ensure the .NET SDK is installed and Visual Studio has NuGet feed access.
- If the chart does not update, check the data service and component bindings in the `Pages` folder.

## Notes

Content is intentionally concise and focused on demonstrating live chart binding patterns in Blazor.