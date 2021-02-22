# Console app

This is the example:

> docker run --rm -it -v $(pwd)/app/ -w /app mcr.microsoft.com/dotnet/sdk:5.0 dotnet run

So you can create a project using the command dotnet new:

> docker run --rm -it -v $(pwd)/app/ -w /app mcr.microsoft.com/dotnet/sdk:5.0 dotnet new

# apsnetcore

In ./aspnetcore is a Dockerfile to build a aspnetcore project
