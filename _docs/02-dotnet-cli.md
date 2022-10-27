# dotnet CLI

dotnet new globaljson
dotnet new sln -n BasicOrchardCore
dotnet new web -n BasicOrchardCore.Web
dotnet sln .\BasicOrchardCore.sln add .\BasicOrchardCore.Web\
dotnet add .\BasicOrchardCore.Web\ package OrchardCore.Application.Cms.Targets


https://localhost:7086/admin
https://localhost:7086/Login?ReturnUrl=%2Fadmin