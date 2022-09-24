# CS Fundamentals
> Computer Science Fundamentals Notes

### 1. SSH

Relevant Video: [Beginners Guide to SSH](https://youtu.be/qWKK_PNHnnA)

A secure protocol for logging into someone else's computer. It was desinged as a replacement of Telnet which was not secure. It uses public-key cryptography to authenticate the remote computer and allow it to authenticate user. It is typically used to log into a remote machine and execute commands however it can also be used for transfering files via SSH file transfer (SFTP) or secure copy (SCP).


### 2. SSL (or TLS)

Relevant Video: [What is SSL & TLS?](https:youtu.be/HMoFvRK4HUo)

A secure protocol for communicating across a network without letting someone in between to sniff or eavesdrop on the message exchanged. It protects the data in three ways: 

* Confidentiality: Data is only accessible by Client and server [Encryption]
* Integrity: Data is not modified between Client and Server [Hashing]
* Authentication: Client/Server are indeed who they say they are [Public Key Infrastructure]]
