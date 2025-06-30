AspireApp is a modern web application that leverages **Blazor** for building interactive, client-side UIs with .NET, and uses **Redis** as a high-performance caching layer to optimize data access and scalability.

## Features

- **Blazor Frontend**: Rich, responsive user interfaces built with C# and Razor components.
- **Redis Caching**: Fast, in-memory data storage to reduce database load and improve performance.
- **.NET Backend**: Seamless integration between frontend and backend using ASP.NET Core.
- **Scalable Architecture**: Designed for cloud deployment and horizontal scaling.

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Redis](https://redis.io/download)
- [Node.js](https://nodejs.org/) (if using Blazor WebAssembly with npm packages)

### Running the App

1. **Start Redis**  
    Ensure Redis is running locally or update the connection string in `appsettings.json`.

2. **Build and Run the App**
    ```bash
    dotnet build
    dotnet run
    ```

3. **Access the App**  
    Open your browser at `http://localhost:5000` (or the configured port).

## Configuration

- Update Redis connection settings in `appsettings.json`:
  ```json
  "Redis": {
     "ConnectionString": "localhost:6379"
  }
  ```

## License

This project is licensed under the MIT License.
