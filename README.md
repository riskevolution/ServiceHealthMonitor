# Risk Evolution Health Status

**Risk Evo Web Services Support**

| Server                                                        | Availability                                                                    
|---------------------------------------------------------------|----------------------------------------------------------------------------------
| [PROD](https://RiskEvolutionInflationService.azurewebsites.net/2001/Inflation/LatestPublications/HealthCheck) | ![uptime](https://uptime.riskevo.com/api/badge/3/uptime/72?style=flat "PROD")
| [UAT](https://TestRiskEvolutionService.azurewebsites.net/2001/Inflation/LatestPublications/HealthCheck)| ![uptime](https://uptime.riskevo.com/api/badge/2/uptime/72?style=flat "UAT")

**Dashboard:** [Risk Evo Services Status](https://uptime.riskevo.com/status/inflation)

**SFTP Services Support**

| Server                                                        | Availability                                                                    
|---------------------------------------------------------------|----------------------------------------------------------------------------------
| [SFTP1](https://sshcheck.com/server/sftp1.riskevolution.com/) | ![uptime](https://uptime.datagrid.de/api/badge/15/uptime/72?style=flat "SFTP1")  
| [SFTP2](https://sshcheck.com/server/sftp2.riskevolution.com/) | ![uptime](https://uptime.datagrid.de/api/badge/207/uptime/72?style=flat "SFTP2") 

**Dashboard:** [Risk Evolution SFTP Status](https://uptime.datagrid.de/status/riskevo)

## API Health Checks

The following health checks are available for monitoring the API services:

### Calendar Rolls Health Check
- **Endpoint:** `/Test/CalendarRolls/HealthCheck`
- **Response:**
    ```json
    {
        "status": "Healthy",
        "timestamp": "2024-08-13T09:49:29.4157556Z",
        "environment": "UAT"
    }
    ```

### Latest Publications Health Check
- **Endpoint:** `/2001/Inflation/LatestPublications/HealthCheck`
- **Response:**
    ```json
    {
        "status": "Healthy",
        "timestamp": "2024-08-13T09:49:29.4157556Z",
        "environment": "UAT"
    }
    ```
