FROM mcr.microsoft.com/dotnet/core/sdk:2.2
LABEL maintainer="Hjörtur Jóhann Vignisson"

ENV ASPNETCORE_URLS http://*:80

COPY . /app
WORKDIR /app

RUN dotnet restore
RUN dotnet build

ENTRYPOINT ["dotnet", "run"]
