# client-server-shell-CLI
### A 4- Phase Project from a shell-CLI to a server-client system with scheduling capabilities

This project is divided into 4 phases:

1. __Phase 1__:
Building a simple CLI shell that simulates 15 different operating system commands. This is implemented using features such as process creating,   interprocess communication, etc. An important feature that was implemented is the use of piped commands. 

2. __Phase 2__:
A single server-client remote shell is implemented using socket communication. It uses operating system concepts such as the usage of sockets, ports and local IP addresses to simulate a connection between a client and a server. The perver processes the command of the client and returns the output. It is also able to handle important features such as connection and disconnection. 

3. __Phase 3__:
Phase 3, adds the feature of multiple clients to connect to one server. This is done through multi-threading. It includes important features such as handling client disconenctions through proper client-server communicaiton. 

4. __Phase 4__:
In this phase, scheduling algorithms are implemented to order the commands sent by multiple clients. The user is allowed to send a dummy program with a desired runtime and the server decides the processing time for each applicaiton using Round Robin Scheduling and Shortest Job First. The server has a realtime clock in the back to synchronize the running of the programs and sending the clients the results. 


### How to run the code. 
- Make sure gnu gcc C++ is installed.
- Unzip the Phase file. 
- use `make clean` and then `make` to recompile all the files.
- run the executable created using `./filename` where filename is *Server* and *Client* or *shell*


***This semester long team project was built as part of the Operating Systems class in collaboration with [Dev Kalavadiya](https://github.com/Dev-Kalavadia).***


