# A simple server for BSD and macOS using 'kqueue()'

written in C++

Srever returns to the client whatever the client sends.
Server handles multiple connections - up to whatever you set.

This approach easily allows 10K connections on one machine.


TIPS:

It is possible to use 'telnet 127.0.0.1 12345' as a client to test this 'echo' server.
