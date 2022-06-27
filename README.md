# Logtail .NET

Logtail uses a highly popular NLog logging library. You can integrate Logtail into your .NET application in just a few simple steps.

Visit our [official docs](https://logtail-main.readme.io/docs/installing-logtail-and-nlog) to learn more about Logtail and .NET!

# Installation

To use Logtail in your .NET project you need to install the following two packages. It can be done from the Visual Studio interface or command line, depending on your preferences.

## Install Logtail package

### In Visual Studio

In Visual Studio, open **NuGet Package Manager Console** by clicking Tools **→ NuGet Package Manager → Package Manager Console**

In the opened console run the following command:

```php
Install-Package Logtail
```

Then run the following command to install `NLog.Extensions.Logging` package:

```php
Install-Package NLog.Extensions.Logging
```

### In PowerShell command line

To install the `Logtail` package using PowerShell, run the following command in your project’s directory:

```powershell
dotnet add package Logtail
```

Then install `NLog.Extensions.Logging` package using the following command:

```powershell
dotnet add package NLog.Extensions.Logging
```

## Install example application

Download or clone the repository to your select project directory.

### Run the example application using Visual Studio

Open the `.csproj` file in the Visual Studio. Then click on the green play button `DotNetLogtail` or press **F5** to run the application.

### Run in the command line

Open the command line in the projects directory and enter the following command:

```powershell
dotnet run
```

This is the expected output:

```powershell
All done! Now, you can check Logtail to see your logs
```
