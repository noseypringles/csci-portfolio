[Back to Portfolio](./)

Python Chatroom
===============

-   **Class:** CSCI 332
-   **Grade:** 
-   **Language(s):** python
-   **Source Code Repository:** [Python Chatroom](https://github.com/noseypringles/Python-Chatroom)  
    (Please [email me](mailto:kequick@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is a simple Chat Room server and allows multiple clients to connect to it using a client-side script. The code uses the concept of sockets and threading. 

## How to view program

Users can download the server and client code (must have python extension) and then open command prompt. They can then choose their IP address and port number.
```bash
cd ../chat-room-server-master/code
python chat_server.py 127.0.0.1 4000
```
```bash
cd ../chat-room-server-master/code
python client.py 127.0.0.1 4000
```

## UI Design

- Everyone who will be using the program needs to be on the same network.
- Anyone who wants to join the chat needs to have the client code on their device.
- The host needs to have the server code running on their device before clients can join (see Fig 1).
- The users who want to join the chat needs to put in the same IP address and port number as the server (see Fig 2).
- This can be run on linux or windows.
- Once connected the users can now freely chat back and forth (see Fig 3 and Fig 4).


![serverRun](/images/csci332Media/serverRun.png)  
Fig 1. Run the server code in terminal.

![clientRun](/images/csci332Media/clientRun.png)  
Fig 2. Run the client code in terminal.

![clientConnected](/images/csci332Media/clientConnected.png)  
Fig 3. On server side, it shows when client joins chat.

![typeChat](/images/csci332Media/typeChat.png)  
Fig 4. On client side, it shows that you can now type.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
