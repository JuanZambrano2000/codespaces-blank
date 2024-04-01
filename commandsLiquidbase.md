liquibase update --username=app_data --password=Ej3mpL0DeP@ssW0rd --url=jdbc:oracle:thin:@dev_low?TNS_ADMIN=/workspaces/codespaces-blank/oracle --changelog-file=newdb.sql 

liquibase update --username=app_data --password=Ej3mpL0DeP@ssW0rd --url=jdbc:oracle:thin:@dev_low?TNS_ADMIN=/workspaces/codespaces-blank/oracle --changelog-file=changelog.json 

liquibase update-sql --username=app_data --password=Ej3mpL0DeP@ssW0rd --url=jdbc:oracle:thin:@dev_low?TNS_ADMIN=/workspaces/codespaces-blank/oracle --changelog-file=changelog.json 