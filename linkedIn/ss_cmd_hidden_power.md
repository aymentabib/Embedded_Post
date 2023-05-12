# ss command hidden power 
## introduction: 
- I do this exploration when checking mosquitto broker.
- i want to know the amount of data sent and receveid by every tcp connection. 
- there is other commands that can get this kind of information but not as I want.
- we will explore therm also in this article 

https://chat.openai.com/c/2fe695ec-5d10-42f5-a199-3c97d688d09b
The Internet of Things (IoT) is expanding at an unprecedented rate, with more and more devices being connected to the internet every day. As a result, managing and monitoring the resulting network traffic is becoming increasingly important. One of the tools commonly used in this context is the Mosquitto broker, which facilitates communication between IoT devices. However, monitoring the broker itself can be challenging without the right tools. In this article, we'll explore how to use the ss command to get detailed information about the TCP connections established with the Mosquitto broker, allowing you to monitor the traffic flowing through this important component of your IoT network. We'll also compare the ss command to other tools that can be used for monitoring network traffic.

- you can get this information but with iftop command using show total  option, but you start counting from the 
  the isntant of command execution not from the begining of tcp connection.
  
- you can use for sure graphic web tools like to monitor all your servers, but in my case I don't need this huge deployment 
   and I would like to supervise and monitor quikly and deeply all the connections of one mosquitto broker.
- 
