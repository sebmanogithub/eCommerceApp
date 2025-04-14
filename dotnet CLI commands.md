dotnet --info

dotnet -h

dotnet new list

- dotnet new sln

- dotnet new webapi -o API -controllers

- dotnet new classlib -o Core

- dotnet new classlib -o Infra

- dotnet sln add API .... Core .... Infra

- dotnet sln list

- dotnet add reference ../Infrastructure

- dotnet restore / dotnet build



dotnet tool install --global dotnet-ef --version 8.0.5

dotnet ef migrations add InitialCreate -s API -p Infrastructure

dotnet ef migrations remove -s API -p Infrastructure

dotnet ef database update -s API -p Infrastructure
