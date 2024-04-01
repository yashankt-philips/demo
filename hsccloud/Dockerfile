FROM mcr.microsoft.com/dotnet/aspnet:6.0 AS base

WORKDIR /hsccloud

COPY . .

EXPOSE 8080

FROM base AS final
WORKDIR /hsccloud

ENTRYPOINT ["dotnet", "Philips.IAP.MockServer.dll"]
