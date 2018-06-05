# NEXTLogisticsWebApp

## Project description

This project was generated with SDK Command Prompt (Angular 5)

$ dotnet new angular -o NEXTLogisticsWebApp

Install @angular/cli

$ npm install
$ npm install -g @angular/cli

All components and services were included using `ng` commands
- ng generate component component-name
- ng generate service service-name

## Development server

Before run this Web App, follow the steps below:

 - clone from github the web service repository

 $ git clone https://github.com/gustavogalvao/NEXTWebAPI.git

 $ cd NEXTWebAPI/

 - run the service app

 $ dotnet publish

 $ dotnet run

 - test web service

 $ curl http://localhost:62081/api/products

 ## With the service app running, run the web app

 $ dotnet publish

 $ dotnet run

 - execute chrome (or another browser --disable-web-security) avoiding CORS

 $ chrome.exe --disable-web-security

 Navigate to `http://localhost:5000/`.
