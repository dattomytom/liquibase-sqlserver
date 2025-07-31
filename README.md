## At Your Local
Step 1 : [Install](https://docs.liquibase.com/start/install/liquibase-windows.html) Liquibase your local <br/>
Step 2 : Clone or downlload this project into your local <br/>
Step 3 : At folder your clone <br/>
  - a. Edit value ***url,user,password*** <br/>
       Example: <br/>
     url=jdbc:sqlserver://<b>liquibasedb.database.windows.net:1433</b>;database=TestDB;encrypt=true;trustServerCertificate=false;hostNameInCertificate=*.database.windows.net;loginTimeout=30; <br/>
     use=sa<br/>
     password=password<br/>
  - b. Run cmd "liquibase update --defaultsFile=liquibase-ci.properties --log-level=debug"

    <img width="1366" height="555" alt="image" src="https://github.com/user-attachments/assets/54a8ca73-c80a-4a48-a2bc-18c874510a2b" />

## At Your Repo: Deploy on MSSQL Server on azure cloud
Step 1 : Fork and push your repo <br/>
Step 2 : Add infomation relation to SQL <br/>
- LIQUIBASE_URL <br/>
- LIQUIBASE_USERNAME <br/>
- LIQUIBASE_PASSWORD <br/>

<img width="1297" height="286" alt="image" src="https://github.com/user-attachments/assets/e75d5cc7-dd84-4c10-b018-47aa94cff5d6" />

Step 3 : Run Action <br/>
**Note *this is [best practice liquibase](https://docs.liquibase.com/concepts/bestpractices.html)***
