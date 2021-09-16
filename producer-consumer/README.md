
Producing means nothing more than sending. A program that sends messages is a producer.

A queue is the name for a post box which lives inside RabbitMQ. Many producers can send messages that go to one queue, and many consumers can try to receive data from one queue.

Consuming has a similar meaning to receiving. A consumer is a program that mostly waits to receive messages.

### To Run
Run `consume.py` first, and then `produce.py`