# MQTT Messaging with RabbitMQ, MongoDB, and Flask

This project implements a client-server system using MQTT messaging via RabbitMQ, with message processing in Python, storage in MongoDB, and a Flask-based API endpoint for data retrieval based on time ranges.

## Project Overview

The project consists of two main components:
1. **MQTT Client:** A Python script that emits MQTT messages every second with a "status" field containing a random value between 0 and 6.
2. **Server:** Handles incoming MQTT messages, processes them to store in MongoDB, and provides a Flask API endpoint to query and retrieve status counts based on specified time ranges.

## Dependencies

Ensure you have the following dependencies installed:
- Python 3.x
- Flask
- Pika (Python client for RabbitMQ)
- Pymongo (Python driver for MongoDB)
- Flask-PyMongo (Flask extension for MongoDB)

You can install dependencies using pip:

pip install Flask pika pymongo Flask-PyMongo
