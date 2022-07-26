# FeralCat

## Run Locally

1. Create .env file for docker environment variables
2. Add the following environment variables into .env:
   ```shell
   FERALCAT_DB_USER="<set-db-user>"
   FERALCAT_DB_USER_PASSWORD="<set-db-password>"
   FERALCAT_KEYCLOAK_ADMIN_PASSWORD="<set-keycloak-admin-user-password>"
   FERALCAT_KEYCLOAK_MANAGER_PASSWORD="<set-keycloak-management-user-password>"
   ```
3. Run the docker compose command:
   ```shell
   docker compose up -d
   ```

## Import to IntelliJ Idea

1. Start [IntelliJ Idea IDE](https://www.jetbrains.com/idea/)
2. Click on `File > Open...`
3. Browse and select `feralcat` from your local folder and click `Open`

## [Accounts Service](accounts-service/README.md)

Accounts service is responsible for maintaining user accounts for the FeralCat application.
