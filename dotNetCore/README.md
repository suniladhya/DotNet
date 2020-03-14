### DotNet core Commands
* dotnet new -h
* dotnet new gitignore
* dotnet new console 
* dotnet new console --name="myFirstCoreApp"
* dotnet run// dotnet build is automatically called
* dotnet add package  newtonsoft.json* 

# ASP.Net Core by Shawn Widermuth
_Goal:_ 
1. core2.1 
2. MVC6
3. ef Core 2.1
4. Angular 6

## Defining ASP.Net Core:

### DotNet core Commands
* dotnet new -h
* dotnet new console 
* dotnet new console --name="myFirstCoreApp"
* dotnet run// dotnet build is automatically called
* dotnet add package  newtonsoft.json* 

notepad myFirstCoreApp.csproj

* dotnet restore gets all the packages it needs.

In 4.x, we see the csprojfile contains the details of all the project file details in it.

To allow ms build to compile & run the project. It is imported to Linux and mac to run the Project.

**But in .Net core it is the Simpler version as stated below:**
```
<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <OutputType>Exe</OutputType>
    <TargetFramework>netcoreapp2.1</TargetFramework>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="newtonsoft.json" Version="12.0.2" />
  </ItemGroup>

</Project>
```
