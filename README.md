# PHP and HTML that deals with an Alien ALR-8800 RFID reader

## There are several components:

1. The php that listens for messages from the Alien reader, parses them, modifies/formats them, and stuffs them into a database. 
2. The database which has a table for messages from the reader and another for items that are tracked by an RFID tag. 
3. The web application that allows you to review tags read by the reader and items that are being tracked by the readers. 

## There is alot to say about the Alien readers, networking issues, email, web servers.
