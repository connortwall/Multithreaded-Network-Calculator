# Multithreaded-Network-Calculator
I created calculator that could work through a network connection, using a thread for each client connection. 
I made a struct type to represent the data associated with a particular client, which includes the client socket file descriptor and a pointer to the shared struct Calc instance. 
I added synchronization to my implementation so that expression evaluations are atomic.
