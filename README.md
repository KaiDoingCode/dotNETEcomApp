# dotNETEcomApp

This is the source code of the ecom application using ASP.NET MVC and Entity Framework Core

This application would be deployed to Azure and the preview link would be updated below when the development is completed.

# Technology
This application use the following technology:

- .NET MVC BUILDING BLOCKS - Models, ViewModels, Views, Partial views, Controllers, ViewComponents etc.
- CRUD OPERATIONS WITH ENTITY FRAMEWORK CORE - SQL Server configuration, EFCore migrations, relationship types, relational and non-relational data etc.
- BUILD RESTFUL SERVICES - Dependency injection, major dependency injection lifetimes, services, and generic base repositories etc.
- .NET IDENTITY FRAMEWORK - Authentication, authorization, cookie-based authentication, role-based UI rendering etc.
- PAYPAL INTEGRATION - Configuring the PayPal checkout library, create and process payments etc.
- AZURE DEPLOYMENT 

# Main features

- User credentials storage, logging in and signing in features.
- Cart storage, payment support with Paypal.
- Create new movie, actors, movie reviews.
- Movie filtering, status update 


# Application demo
![E-commerce Demo 1](https://public-info-tuphung.s3.eu-central-1.amazonaws.com/ecom-demo-1.png)
![E-commerce Demo 2](https://public-info-tuphung.s3.eu-central-1.amazonaws.com/ecom-demo-2.png)
![E-commerce Demo 3](https://public-info-tuphung.s3.eu-central-1.amazonaws.com/ecom-demo-3.png)
![E-commerce Demo 4](https://public-info-tuphung.s3.eu-central-1.amazonaws.com/ecom-demo-4.png)


# How to run them from your computer

* Clone the repo
```
git clone https://github.com/KaiDoingCode/dotNETEcomApp.git
```

* Click the eTickets.sln file to open it in Visual Studio GUI

* Install dependencies

* Install Docker

* Run this command in your Terminal/Ubuntu to initialize your local SQL database via Docker

```
sudo docker run --cap-add SYS_PTRACE -e 'ACCEPT_EULA=1' -e 'MSSQL_SA_PASSWORD=Strong.Pwd-123' -p 1433:1433 --name ecommerce_app_db -d mcr.microsoft.com/azure-sql-edge
```

* Navigate into the eTickets folder `cd eTickets`

* Run `dotnet run` to build the project locally

* Open `https://localhost:5001` on your browser to view the homepage of the project on your local machine




