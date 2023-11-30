tcp_client: tcpclient.c
	gcc tcpclient.c -o tcpclient

tcp_server: tcpserver.c
	gcc tcpserver.c -o tcpserver

server_tcp:
	./tcpserver
	./tcpclient 127.0.0.1 10050

udp_client: udpclient.c
	gcc udpclient.c -o udp_client

udp_server: udpserver.c
	gcc udpserver.c -o udp_server

server_udp:
	./udp_server 27001
	./udp_client 127.0.0.1 27001