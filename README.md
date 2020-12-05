# Welcome to ASP.NET Core

## This application consists of:

*   Sample pages using [ASP.NET Core MVC](http://dot.net) with [Razor](https://docs.asp.net/en/latest/mvc/overview.html#razor-view-engine)
*   [Bower](https://go.microsoft.com/fwlink/?LinkId=518004&WT.mc_id=devops-0000-dbrown) for managing client-side libraries
*   Themed using [Bootstrap](https://go.microsoft.com/fwlink/?LinkID=398939&WT.mc_id=devops-0000-dbrown)

## This application was developed with:

*   [Visual Studio Code](https://www.visualstudio.com/products/code-vs?WT.mc_id=devops-0000-dbrown)
*   [Team Services](https://www.visualstudio.com/products/visual-studio-team-services-vs?WT.mc_id=devops-0000-dbrown)
*   [Yeoman](http://yeoman.io/)

## This application can deploy to:

*   [Azure App Service](https://azure.microsoft.com/services/app-service/?WT.mc_id=devops-0000-dbrown)
*   [Azure IaaS Linux via Docker](https://azure.microsoft.com/services/virtual-machines/?WT.mc_id=devops-0000-dbrown)
*   [Azure Container Service](https://azure.microsoft.com/services/container-service/?WT.mc_id=devops-0000-dbrown)

## The application is monitored by

* [Application Insights](https://docs.microsoft.com/azure/application-insights/app-insights-nodejs?WT.mc_id=devops-0000-dbrown)

To develop locally create an environment variable named APPINSIGHTS_INSTRUMENTATIONKEY and set it to the instrumentation key from Azure. You can also add the following snippet to your appsettings.json file.

```json
// Replace key with value from Azure
"ApplicationInsights": {
  "InstrumentationKey": "10101010-1010-1010-1010-101010101010"
}
```