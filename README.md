# the-rabbit-with-the-python
Just the basic implementations of RabbitMQ using Python

---

Docker script to run RabbitMQ:
```
# for RabbitMQ 3.9, the latest series
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management

# for RabbitMQ 3.8,
# 3.8.x support timeline: https://www.rabbitmq.com/versions.html
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.8-management
```