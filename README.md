
# Weather Forecast Application

A simple ASP.NET Core MVC application that displays the weather forecast for various cities. This application demonstrates basic MVC concepts, including views, controllers, and model binding.

## Features

- **City Weather Overview**: Displays a list of cities with their respective weather conditions.
- **Detailed Weather View**: Each city has a dedicated detail page that shows more information.
- **Dynamic Card Backgrounds**: The temperature determines the background color of the weather card.
  - Blue for temperatures between 0°F and 44°F
  - Green for temperatures between 45°F and 74°F
  - Red for temperatures above 74°F

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/) with C# extension
- A web browser for viewing the application

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MahmoodElbadri/Layout-Views-Assignment.git
   cd weather-forecast-app
   ```

2. **Open the project in Visual Studio or VS Code.**

3. **Restore dependencies and build the project:**
   ```bash
   dotnet restore
   dotnet build
   ```

4. **Run the application:**
   ```bash
   dotnet run
   ```

## Project Structure

- **Controllers:**
  - `HomeController.cs`: Manages the routing and logic for displaying the weather overview and detailed city weather.
  
- **Views:**
  - `Index.cshtml`: Displays the list of cities with their current weather.
  - `Weather.cshtml`: Displays detailed weather information for a specific city.

- **Models:**
  - `CityWeather.cs`: Represents the weather data for a city, including temperature, city name, and unique city code.

- **CSS Classes:**
  - `button-blue-back`: Background color for cold temperatures.
  - `button-green-back`: Background color for moderate temperatures.
  - `button-red-back`: Background color for hot temperatures.
