# RsaCryptography
**Assignment - Cryptography Using The RSA Algorithm.**

This assignment will be solved in Java utilizing the BigInteger class and communication through stream sockets. Before beginning to work on the assignment, read through the Cryptography section in 4.5 Applications of Congruences and/or the
Swedish material on cryptography presented at the course webb (kap6.pdf and ovnkap6.pdf). Also get the
Java programs P2PTCP.java and StringSender.java. Rewrite the P2PTCP program so that when it runs as
a server, it publishes a public RSA key with a size specified by a command line argument. Any time a client
connects to a server, the server sends this key to the client which in turn receives it and encrypts a random
integer between 1 and 100 and sends to the server. The server then decrypts the integer and writes it on the
screen. Work with sending objects of the class BigInteger in text format (String). (If you wish you can also
serialize the objects which would be a more object-oriented approach, choose what you feel most comfortable
with.)
