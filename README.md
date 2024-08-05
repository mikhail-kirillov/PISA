# PISA - Application for Private Information Exchange

## Description

A console application in Java for communication.

## Features

- **Console Application**: Convenient and simple text interface.
- **Socket Usage**: Supports communication in a local network and over the Internet.
- **Message Encryption**: All messages are encrypted using a public RSA key with a key length of 2048 bits.
- **Dynamic Key Generation**: New keys are created with each new communication session.
- **Notifications**: When one participant exits, the other receives a notification, and the application terminates.

## Requirements

Java version 8 or higher is required to run the application.

## Usage

After starting the application, follow the on-screen instructions to begin communication. You will need to enter the IP address of your interlocutor.

## Important Information

The application works on sockets. Therefore, there are two scenarios for using this program:

1. Communication within a local network.
2. Communication over the World Wide Web.

In both cases, you must have open ports. To find out each other's IP addresses, you and your interlocutor need to use a third-party communication channel.

When you start and enter the necessary information, the application creates a server to receive messages and a client to send your messages.

## Contribution to the Project

If you have suggestions for improving the application or find bugs, feel free to create an Issue or Pull Request in the repository.

Good luck with your communication!

---

Date: 09-03-2020
