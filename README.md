The purpose of this project is to enable two android devices to share messages with each other.

This project can be tested by running two android emulators and installing the app on both the devices 
and then sending messages between the devices using the application interface.

Each device will have a listener which opens a server socket to listen to incoming messages on a specified Inet address 
and display on the device. This socket will be opened using an asynchronous task.

While sending a message, another asynchronous task will be executed which will open a socket connection to the device 
to which the message is being sent by specifying the recievers Inet Address.