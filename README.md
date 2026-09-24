# How to Create a Spline Chart in Blazor Chart

## Overview

This sample demonstrates how to create a spline chart using Syncfusion [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts). The application renders category-based sales data and visualizes the values using a spline series that connects data points with smooth curved lines.

The sample shows how to bind a collection of strongly typed C# objects to a chart series and map object properties to chart axes. By configuring the series type as `ChartSeriesType.Spline`, the chart provides a smooth representation of trends between individual data points while preserving the underlying data values.

## Key Features

- Uses the `SfChart` component to render the chart.
- Sets the chart title through the `Title` property.
- Configures the primary X-axis using `ChartPrimaryXAxis`.
- Sets `ValueType="Syncfusion.Blazor.Charts.ValueType.Category"` to display categorical values on the X-axis.
- Uses `ChartSeriesCollection` to host chart series definitions.
- Binds data to the chart through the `DataSource` property.
- Maps category values using `XName="X"`.
- Maps numeric values using `YName="YValue"`.
- Configures the series type using `Type="ChartSeriesType.Spline"` to render smooth curves between data points.
- Demonstrates binding data from a `List<ChartData>` collection.
- Uses a strongly typed `ChartData` model with `X` and `YValue` properties.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `Spline/Spline.csproj` project file in Visual Studio 2022.
3. Restore NuGet packages when prompted.
4. Build the project.
5. Run the application using **Ctrl + F5**.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
cd Spline
dotnet restore
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

`Pages/Index.razor` - Implements the spline chart sample using `SfChart`, `ChartPrimaryXAxis`, `ChartSeriesCollection`, and `ChartSeries`.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/getting-started
- Spline Chart Feature Overview: https://www.syncfusion.com/blazor-components/blazor-charts/chart-types/spline-chart

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.