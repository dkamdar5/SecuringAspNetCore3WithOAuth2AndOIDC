Pull the SQL Server 2017 container
sudo docker pull mcr.microsoft.com/mssql/server

sudo docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=YourStrong!Passw0rd' -p 1433:1433 -d mcr.microsoft.com/mssql/server

docker ps -a
