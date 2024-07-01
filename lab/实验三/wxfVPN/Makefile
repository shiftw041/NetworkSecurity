all: 
	gcc -o myclient myclient.c -lssl -lcrypto -lpthread -w
	gcc -o myserver myserver.c -lssl -lcrypto -lpthread -lcrypt -w
	sudo docker cp ../wxfVPN HostU:/
	sudo docker cp ../wxfVPN HostU2:/

clean: 
	rm myclient myserver
