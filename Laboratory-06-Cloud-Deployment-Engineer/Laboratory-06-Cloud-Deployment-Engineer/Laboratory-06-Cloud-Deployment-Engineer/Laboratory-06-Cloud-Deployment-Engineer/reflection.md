# Mission 6 – Cloud Deployment Engineer Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because it puts the configuration of multiple containers in one place. Instead of typing commands separately, I can use one command to deploy the application and its database. It also makes the setup easier to repeat and manage.

YAML indentation is important because it shows the relationship between the different sections and settings. If I use incorrect indentation or a Tab instead of spaces, Docker Compose may fail to read the file or may report a configuration error. This is why I need to check the formatting carefully before deploying the application.

Environment variables, such as `MYSQL_PASSWORD` and `MYSQL_DATABASE`, provide the configuration values needed by the containers. They help Nextcloud connect to the correct database using the required credentials. However, sensitive credentials should be handled carefully and should not be exposed in public repositories in real-world projects.

Deploying Nextcloud and MariaDB using Docker Compose helps me understand how different services work together. Instead of managing only one container, I can configure a web application and a database as part of one system. I expect to feel more confident once I successfully access the Nextcloud setup page through my browser.

Since Mission 1, my understanding of cloud computing has grown from learning basic concepts to practicing how cloud services can be deployed and managed. I have learned to use Docker, work with storage solutions, document my activities in Markdown, and maintain my GitHub portfolio. This mission also introduces me to Infrastructure as Code, where configurations are written in files instead of relying only on manual commands. I believe these skills will help me understand how real-world cloud applications are deployed and maintained.
