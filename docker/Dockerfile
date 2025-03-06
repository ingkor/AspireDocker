FROM mcr.microsoft.com/mssql/server:2022-latest

# Set environment variables
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrong@Passw0rd

# Expose the SQL Server port
EXPOSE 1433

# Create a directory for database files
WORKDIR /var/opt/mssql/data

# The container will start SQL Server automatically
