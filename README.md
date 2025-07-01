# RabbitMQ message queue consumer
This project was created for testing the correct publishing of messages into a RabbitMQ queue

## Use it yourself
To get it running, make sure to have python and pika installed.
Create a folder for cloning the repository
```
git clone https://github.com/alejo190404/muebles-sas-consumer
cd muebles-sas-consumer
```
Run the command to see the outputs
```
python receive.py
```
The running terminal will showcase the messages present in the queue

## Requirements
The following requirements are needed for running the project
- [Pika](https://pypi.org/project/pika/)
- [Python 3](https://www.python.org/downloads/)
- Running RabbitMQ server/container
