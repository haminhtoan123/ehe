FROM mcr.microsoft.com/dotnet/sdk:6.0 as build 

ENV ASPNETCORE_URLS=https://+:5147

WORKDIR /var/www/hehe

COPY . .

EXPOSE 7147 5147

ENTRYPOINT ["/bin/bash", "-c", "dotnet dev-certs https && dotnet restore && dotnet run"]