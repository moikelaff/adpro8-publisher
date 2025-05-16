1. How much data your publisher program will send to the message broker in one
run?
    my program will send 5 UserCreatedEventMessage objects in one iteration,
    each message contains the id from 1 to 5, and a username like 2106750446-amir and such. all these messages are published to the user_created topic

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?
    this url is the connection string to connect to the RabbitMQ server, it contains the protocol (amqp), the username (guest), the password (guest), the host (localhost), and the port (5672). This url is used by both publisher and subscriber programs to connect to the same RabbitMQ server.

![alt text](image.png)