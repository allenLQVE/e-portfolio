---
layout: post
tags: [Java, Web Socket, Java FX]
---

<img src="assets/images/screenshot-chatapp1.PNG" alt="screenshot of Chat application" style="width: 49%; display: inline;">
<img src="assets/images/screenshot-chatapp2.PNG" alt="screenshot of Chat application" style="width: 49%; display: inline;">
<hr/>

This is an application that allows users to chat with other people who are connecting to the server in different chat rooms. \
It connects users and servers through web sockets and uses broadcasts to send messages with multicast sockets. \
The GUI is built with Java FX and stores the user information in Java binary files. It includes a login page which allows user to login and create new user. After login, the user will have the chat rooms that they joined. There is also buttons for joining new room or leaving a room. After enter a room, there will be a panel showing the chats, a panel shows the people inside the room, and a bar where the user can type and send message.

[GitHub Link](https://github.com/allenLQVE/Chat_Application)