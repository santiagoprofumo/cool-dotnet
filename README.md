# Developer Roadmap
- **AspNetCore Developer Roadmap**: A comprehensive guide for .NET developers outlining the skills and path needed for development. [GitHub](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap)

# Essential nuget packages
## Database
- **Dapper**: A lightweight and fast ORM for .NET, known for its simplicity. [GitHub](https://github.com/DapperLib/Dapper)
- **Dapper-Extensions**: Dapper Extensions is a small library that complements Dapper by adding basic CRUD operations (Get, Insert, Update, Delete) for your POCOs. [GitHub](https://github.com/tmsmith/Dapper-Extensions)
- **RepoDB**: A hybrid ORM library for .NET, offering both ORM and direct SQL execution. [GitHub](https://github.com/mikependon/RepoDB)
- **LiteDB**: A NoSQL database for .NET, ideal for local storage solutions. [GitHub](https://github.com/litedb-org/LiteDB)
- **SqlKata**: A SQL query builder for .NET, facilitating complex query creation. [GitHub](https://github.com/sqlkata/querybuilder)
- **DbUp**: A tool for managing database migrations in .NET applications. [GitHub](https://github.com/DbUp/DbUp)
- **FluentMigrator**: A migration framework for .NET, allowing for versioned database changes. [GitHub](https://github.com/fluentmigrator/fluentmigrator)

## API
- **Swashbuckle**: Generates Swagger/OpenAPI documentation for .NET APIs. [GitHub](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
- **OpenApi**: Provides OpenAPI support for .NET 9+ applications. [NuGet](https://www.nuget.org/packages/Microsoft.AspNetCore.OpenApi/)
- **RestSharp**: A simple REST client for .NET, useful for consuming APIs. [GitHub](https://github.com/restsharp/RestSharp)
- **Flurl**: Fluent URL builder and testable HTTP client for .NET. [GitHub](https://github.com/tmenier/Flurl)
- **gRPC**: A high-performance RPC framework for .NET applications. [GitHub](https://github.com/grpc/grpc-dotnet)
- **Yarp**: A reverse proxy and API gateway for .NET applications. [GitHub](https://github.com/dotnet/yarp)

## Job Scheduling
- **NCronJob**: A lightweight library for scheduling jobs in .NET applications. [GitHub](https://github.com/NCronJob-Dev/NCronJob)
- **Coravel**: A library for scheduling and background tasks in .NET. [GitHub](https://github.com/jamesmh/coravel)
- **Hangfire**: A library for easy background processing in .NET applications. [GitHub](https://github.com/HangfireIO/Hangfire)
- **Quartz**: A job scheduling system for .NET applications. [GitHub](https://github.com/quartznet/quartznet)

## DateTime
- **Noda Time**: A library for date and time handling, offering a more comprehensive model than .NET's built-in types. [GitHub](https://github.com/nodatime/nodatime)
- **DateTimeExtensions**: Provides additional functionalities for date and time manipulation. [GitHub](https://github.com/joaomatossilva/DateTimeExtensions)

## Entity Mapping
- **Mapperly**: A code generation library for mapping objects in .NET applications. [GitHub](https://github.com/riok/mapperly)
- **Mapster**: A fast object mapper for .NET, known for its performance. [GitHub](https://github.com/MapsterMapper/Mapster)

## Message Orchestration
- **Rebus**: Simple and lean service bus implementation for .NET. [GitHub](https://github.com/rebus-org/Rebus/)
- **Silverback**: Silverback is a simple but feature-rich message bus for .NET core (it currently supports Kafka, RabbitMQ and MQTT). [GitHub](https://github.com/BEagle1984/silverback)
- **SlimMessageBus**: Lightweight message bus interface for .NET (pub/sub and request-response) with transport plugins for popular message brokers. [GitHub](https://github.com/zarusz/SlimMessageBus)

## Logging and Monitoring
- **Serilog.Extensions.Logging.File**: A lightweight logging library for structured data. [GitHub](https://github.com/serilog/serilog-extensions-logging-file)
- **Serilog**: A full-featured logging library for structured data in .NET applications. [GitHub](https://github.com/serilog/serilog)
- **Sejil**: Capture, view and filter your ASP.net core log events right from your app. [GitHub](https://github.com/alaatm/Sejil)
- **WatchDog**: A simple monitoring tool for .NET applications. [GitHub](https://github.com/IzyPro/WatchDog)

## Validation
- **Polly**: A library for resilience and transient-fault handling, providing retry policies. [GitHub](https://github.com/App-vNext/Polly)
- **FluentValidations**: A library for building strongly-typed validation rules in .NET applications. [GitHub](https://github.com/FluentValidation/FluentValidation)

## Testing
- **AutoFixture**: A library for auto-generating test data in .NET applications. [GitHub](https://github.com/AutoFixture/AutoFixture)
- **Bogus**: A simple fake data generator for .NET applications. [GitHub](https://github.com/bchavez/Bogus)
- **Moq**: A popular mocking library for .NET applications. [GitHub](https://github.com/moq/moq)
- **NSubstitute**: A friendly substitute for .NET mocking. [GitHub](https://github.com/nsubstitute/NSubstitute)
- **FluentAssertions**: A library for asserting conditions in unit tests. [GitHub](https://github.com/fluentassertions/fluentassertions)

## File Handling
- **CsvHelper**: A library for reading and writing CSV files in .NET applications. [GitHub](https://github.com/JoshClose/CsvHelper)
- **Sep**: A fast CSV parser for .NET applications. [GitHub](https://github.com/nietras/Sep/)
- **ClosedXML**: A library for working with Excel files in .NET applications. [GitHub](https://github.com/ClosedXML/ClosedXML)
- **ExcelDataReader**: A lightweight library for reading Excel files. [GitHub](https://github.com/ExcelDataReader/ExcelDataReader)
- **WkHtmlToPdf-DotNet**: A library for converting HTML to PDF in .NET applications. [GitHub](https://github.com/HakanL/WkHtmlToPdf-DotNet)

## WebSockets
- **SignalR**: A library for adding real-time web functionality to .NET applications. [GitHub](https://github.com/SignalR/SignalR)

## State Machine
- **Stateless**: A lightweight state machine library for .NET applications. [GitHub](https://github.com/dotnet-state-machine/stateless)

## AI
- **OllamaSharp**: The easiest way to use the Ollama API in .NET. [GitHub](https://github.com/awaescher/OllamaSharp)
- **LLamaSharp**: A library for local language models in .NET applications. [GitHub](https://github.com/SciSharp/LLamaSharp)
- **OpenAI**: A library for accessing OpenAI's API from .NET applications. [GitHub](https://github.com/openai/openai-dotnet)
- **Semantic Kernel**: A library for integrating AI into .NET applications. [GitHub](https://github.com/microsoft/semantic-kernel)

## Miscellaneous
- **Humanizer**: A library for manipulating and displaying strings in a human-friendly way. [GitHub](https://github.com/Humanizr/Humanizer)
- **SmartEnum**: A library for creating enumeration classes in .NET applications. [GitHub](https://github.com/ardalis/SmartEnum)
- **Spectre.Console**: A library for creating beautiful console applications in .NET. [GitHub](https://github.com/spectreconsole/spectre.console)

## Javascript engines
- **Jint**: Javascript Interpreter for .NET. [GitHub](https://github.com/sebastienros/jint)
- **Jurassic**: A .NET library to parse and execute JavaScript code. [GitHub](https://github.com/paulbartrum/jurassic)

## Extension Methods
- **ExtensionMethods**: C# Extension Methods | Over 1000 extension methods. [GitHub](https://github.com/zzzprojects/Z.ExtensionMethods)
- **C# extension methods collection**: Site with collection of extension methods. [C#](https://www.extensionmethod.net/csharp)
