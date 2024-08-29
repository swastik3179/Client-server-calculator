CLIENT-SERVER-CALCULATOR
 A basic TCP-based client-server application in Java, designed to perform basic arithmetic operations (addition, subtraction, multiplication, and division). 
 The client sends arithmetic expressions to the server, which processes the expressions and sends the results back to the client.

FUNCTIONS:-
CLIENT (Calc_Client.java):
--The client program runs on the user's machine and connects to a server using a socket.
--The client reads arithmetic expressions from the user, sends them to the server, and displays the result received from the server.
--The connection between the client and server remains active until the user types "end" to terminate it.

SERVER (server.java):
--The server listens for connections on a specified IP address and port.
--Upon receiving a connection, the server waits for arithmetic expressions from the client, processes them, and sends back the results.
--The server can handle basic operations: addition, subtraction, multiplication, and division.


PRACTICAL IMPLEMENTATIONS:-
1. Simple Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
2. TCP Communication: Demonstrates basic client-server communication using TCP sockets in Java.
3. Interactive: Continuous interaction between client and server until the user decides to terminate the session.
