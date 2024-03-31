# Ops Reading 7
## Network Connectivity
https://www.ssh.com/academy/ssh/protocol

1) What is the Secure Shell (SSH) Protocol? The SSH is a method for secure remote login from one computer to another.
2) What are the typical uses of the SSH protocol?
       - providing secure access for users and automated processes
       - interactive and automated file transfers
       - issuing remote commands
       - managing network infrastructure and other mission-critical system components
3) How does the SSH protocol work? The protocol works in the "client-server model." This means that the connections is established by the SSH client connecting to the SSH server. The client drives the connection setup processes using public key cryptography to verify the identity of the SSH server. 
4) How is the data kept safe when transmitted between the SSH client and server? After initial setup the SSH protocol uses "strong symmetric encryption" and "hashing algorithms" to ensure the privacy and integrity of the data exchanged.
5) What is SFTP? SFTP is the most widely used secure file transfer protocol. It runs over SSH.

## What I want to learn more about
I'd like to learn more about what can go wrong. What are the risks? How much can human error come into play?
