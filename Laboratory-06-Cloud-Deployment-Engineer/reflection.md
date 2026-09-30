# Mission 6 Reflection

## Reflection

Using Docker Compose gave me a better understanding of how deployment configurations can be organized. The services needed by the application were described in one YAML file, which reduces the need to configure each container manually whenever the application needs to be started.

I also learned why YAML indentation cannot be ignored. The spaces determine the relationship between the different configuration settings. If the indentation is wrong or a Tab is used where spaces should be used, Docker Compose may not recognize the structure correctly and the deployment may produce an error.

The environment variables provide configuration values that the containers need. `MYSQL_DATABASE`, `MYSQL_USER`, and `MYSQL_PASSWORD` provide database-related information, while `MYSQL_HOST` tells the Nextcloud service which database service it should connect to. This showed me how containers can exchange configuration information without putting everything into one command.

After starting the services, accessing the Nextcloud setup page through the browser made the deployment process easier to understand. I could see the practical result of the configuration that was created in the terminal.

Since Mission 1, I have gained a broader understanding of Cloud Computing. I now recognize how containerized applications can use separate services for different purposes and how configuration files can help automate deployment. This mission also introduced me to a more structured way of thinking about cloud infrastructure.
