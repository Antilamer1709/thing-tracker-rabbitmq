# thing-tracker-rabbitmq
RabbitMQ in docker container for https://github.com/Antilamer1709/thing-tracker

# To run: 
docker run -d -e RABBITMQ_NODENAME=my-rabbit --name rabbitmq -p 5672:5672 -p 15672:15672 -p 61613:61613 antilamer/rabbitmq-stomp:3.7

# Exposed ports:

5672 => RabbitMQ default node port (transport)

15672 => RabbitMQ web management (http access)

61613 => RabbitMQ STOMP broker port (transport)
