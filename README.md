# Chat Project

Server start:

1) Launch Terminal
2) gcc server.c -o server
3) ./server <port> (4837)

Client start:

1) Launch Terminal
2) ipconfig getifaddr en0 (for LAN en1)
3) gcc client.c -pthread -o client
4) ./client <ip> <port> <nickname>

