# ASP.NET MVC Gantt Chart Sample

Repository Description: Sample ASP.NET MVC 5 application demonstrating Syncfusion Essential JS 2 Gantt chart usage with hierarchical tasks, dependencies, and edit toolbar actions.

## Overview

This project shows a hierarchical Gantt chart using Syncfusion EJ2 components in an ASP.NET MVC 5 application. It includes parent and child tasks, scheduled dates, durations, percent complete values, and task dependencies.

- Uses ASP.NET MVC 5 on .NET Framework 4.6.1
- Uses `Syncfusion.EJ2.MVC5` and `Syncfusion.EJ2.JavaScript`
- Loads Syncfusion EJ2 CSS and scripts from CDN in `Views/Shared/_Layout.cshtml`
- Provides inline sample data from `Controllers/HomeController.cs`

## Features

- Parent / child task hierarchy
- Start and end dates
- Duration and percent complete
- Task dependencies
- Add / edit / delete task support
- Expand all / collapse all toolbar actions

## Prerequisites

- Visual Studio 2022 or later
- .NET Framework 4.6.1 development workload
- NuGet package restore enabled

## Running the project

1. Open `SimpleMvcGantt/SimpleMvcGantt.sln` in Visual Studio.
2. Restore NuGet packages if needed.
3. Build the solution.
4. Run the project using IIS Express or your preferred web server.
5. Navigate to the home page to view the Gantt chart.

## Notes

- The sample uses inline C# model data for demonstration.
- Restore Syncfusion packages from NuGet if binaries are missing.
