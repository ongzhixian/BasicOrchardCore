# dotnet CLI

dotnet new globaljson
dotnet new sln -n BasicOrchardCore
dotnet new web -n BasicOrchardCore.Web
dotnet sln .\BasicOrchardCore.sln add .\BasicOrchardCore.Web\
dotnet add .\BasicOrchardCore.Web\ package OrchardCore.Application.Cms.Targets


https://localhost:7086/admin
https://localhost:7086/Login?ReturnUrl=%2Fadmin


# Orchard Core NuGet meta packages

1.  OrchardCore.Application.Cms.Core.Targets
2.  OrchardCore.Application.Cms.Targets

`OrchardCore.Application.Cms.Core.Targets` is intended for use when:

1. Developing a Decoupled Web Site
1. Developing a Headless Web Site
1. Developing a Themed Web Site from scratch

contains the minimum you need to setup an Orchard Core installation. 
It contains TheAdmin theme, and two recipes to base your installation on, but no front end themes.

`OrchardCore.Application.Cms.Targets` contains all of the above plus

1. Setup recipes for the Themes
1. Multiple CMS Starter Themes

Recipes in Orchard Core help you get your site setup by enabling features, and / or creating content types, and content for your site.

Orchard Core Themes can contain Razor or Liquid views, and by default use Orchard Core Display Management techniques to render content.

# Orchard CMS templates

dotnet new -i OrchardCore.ProjectTemplates::1.4.0

