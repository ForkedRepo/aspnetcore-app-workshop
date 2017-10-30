FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 56009
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "BackEnd.dll"]
