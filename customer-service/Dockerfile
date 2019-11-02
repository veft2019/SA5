FROM mcr.microsoft.com/dotnet/core/sdk:2.2
LABEL maintainer="Hjörtur J, Ívar K, Guðrún M"

ENV ASPNETCORE_URLS http://*:80
ENV ASPNETCORE_ENVIRONMENT Production

COPY . /app
WORKDIR /app
RUN dotnet restore
WORKDIR /app/customer-service

#RUN dotnet restore
#RUN dotnet build

# Not working
ENTRYPOINT ["dotnet", "run"]
