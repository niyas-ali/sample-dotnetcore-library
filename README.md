## Sample dotnet core library app


This repository can be used to test a sample .NET Core library for generating NuGet packages.


***Packing NuGet library***

Dotnet Restore and Build

```
 dotnet restore
 
 dotnet build -c Release --no-restore
```

NuGet Pack

```
 dotnet pack -c Release -o ./nuget 
```