Question 1: How do you specify a TCP socket in Python?
ANS: Use this parameter (socket.SOCK_STREAM) when initializing your socket

Question 2: What is the difference between a client socket and a server socket in Python?
ANS: Server socket bind the host and port but client socket doesn't need to do that. Client socket connects to a host but a server socket doesn't.

Question 3: How do we instruct the OS to let us reuse the same bind port?
ANS: We do this by adding this parameter (socket.SO_REUSEADDR) so that the port will forcibly be used in an event that it is occuped by a different server

Question 4: What information do we get about incoming connections?
ANS: We get the ip address and port of the incoming connections

Question 5: What is returned by recv() from the server after it is done sending the HTTP request?
ANS: recv() return the full http response (including header & body)

Question 6: Provide a link to your code on GitHub.