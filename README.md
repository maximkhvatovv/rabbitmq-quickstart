# rabbitmq-quickstart

1. Run in docker
```
docker run -d --name my-rabbit -p 5672:5672 -p 15672:15672 --hostname rabbithostname -e RABBITMQ_DEFAULT_USER=rabbit -e RABBITMQ_DEFAULT_PASS=rabbitpassword rabbitmq:3-management
```
