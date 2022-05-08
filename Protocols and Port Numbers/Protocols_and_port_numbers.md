# Protocols and Port Numbers

All of these protocols are layer 7 (application) protocols.
Every layer 7 protocol has a layer 4 (transport) component. 

## HTTP / HTTPS 

HTTP use port 80 by default and HTTPS use 443

## File Transfer FTP, sFTP (secure) TFTP (trivial)

sFTP encrypts the file.

Goes both directions from server to client or client to server. 

Trivial is used for small file transfers or quick file transfers, not worrying about authentication and firewalls.

SMB (server message block) network drives / file share.

Ports: 
FTP 20 and 21
sFTP 22
TFTP 69
SMB 445