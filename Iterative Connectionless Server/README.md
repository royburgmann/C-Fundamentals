An example of an Iterative Connectionless Server and Client
The server will accept a UDP message consisting of a text string sent to it by
a client process. The sever will take the string and send it back to the client
in reverse character order.
For UDP_Server.c
    Compile with UDP_Server.c -o server
    Use : client "port number" "no. of iterations"
For UDP_Client.c
    Compile with UDP_Client.c -o client
    Use : client "hostname" "port number" "string" 
    Note: Ensure Connectionless Server is running before using client
NOTE: This is an exercise from a previous unit. Alterations have been made.