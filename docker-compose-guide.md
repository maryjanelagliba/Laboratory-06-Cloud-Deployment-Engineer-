**What does the services: block do?**
The **services: block** defines the services or containers that will run in the application. It specifies details such as the service name, 
image, ports, and other settings.

**How did the Nextcloud app container know how to find the database container? (Hint: Look at the MYSQL_HOST environment variable)
**
The Nextcloud app container knows how to find the database container through the **MYSQL_HOST** environment variable. It uses the database 
service name as the hostname to connect to the MySQL container.

**What is the difference between docker run (which you used in Mission 4) and docker-compose up -d?**
**docker run** starts a single container using a command with its settings. **docker-compose up -d** starts multiple related containers and 
services together using a configuration file. It also runs them in the background, making it easier to manage multi-container applications.

