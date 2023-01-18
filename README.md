# dotNETEcomApp

This is the source code of the ecom application using ASP.NET MVC and Entity Framework Core

This application would be deployed to Azure and the preview link would be updated below when the development is completed.
📌 Preview link: 

# Technology
This application use the following technology:

- .NET MVC BUILDING BLOCKS - Models, ViewModels, Views, Partial views, Controllers, ViewComponents etc.
- CRUD OPERATIONS WITH ENTITY FRAMEWORK CORE - SQL Server configuration, EFCore migrations, relationship types, relational and non-relational data etc.
- BUILD RESTFUL SERVICES - Dependency injection, major dependency injection lifetimes, services, and generic base repositories etc.
- .NET IDENTITY FRAMEWORK - Authentication, authorization, cookie-based authentication, role-based UI rendering etc.
- PAYPAL INTEGRATION - Configuring the PayPal checkout library, create and process payments etc.
- AZURE DEPLOYMENT 


# How to run them from your computer
You can open the eTickets.sln on Visual Studio and run the source code directly from your computer

* Clone the repo

* Click the eTickets.sln file to open it in Visual Studio GUI

* Install dependencies

* Navigate into the eTickets folder `cd eTickets`

* Run `dotnet run` to build the project locally

# Notes
* The connection string may vary based on the OS of your computer. If you use Windows and use MySQL database management rather than docker image, then change the connectionstring into

```
"DefaultConnectionString": "Data Source=etr\\sqlserver;Initial Catalog=ecommerce-app-db;Integrated Security=True;Pooling=False"
```

* The app is still in development and is still being updated. The finished preview link and final project would be updated in the latest time.
