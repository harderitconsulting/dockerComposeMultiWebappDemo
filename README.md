# Multiple Webapps Inside Docker Compose Setup

- Learn how to setup a custom network for your containers: container A talks to container
- Learn how to run multiple webapps inside Docker containers on different ports

- Create the network with $docker network create skynet
- Run with $docker-compose up
- Stop with $<Ctrl + C>
- Clean up from time to time with $docker system prune -a -f

- access via http://localhost:8080/sample
- access via http://localhost:8081/sample

