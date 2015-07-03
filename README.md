Chatroom
=========

Miniature IRC-style chatroom written in about 300 lines of Python. Stores users and their passwords persistently.

Todo:

* Make sure a user can only be online in one session. 
       *Block `/nick` changes to that user as well as new login attempts.
* Implement a `/changepass` command with optional <username> and <pass> parameters to change a user's password. Current password required of course.
* ~~Implement a `/nick` command to change the current connection's username~~
* Look into writing a client program to smooth out the experience and get rid of the usability problems with Telnet
* Store some statistics about users, like total number of messages sent
* ~~Make the users file an absolute filepath~~
* Implement a `/help` command
* Implement a `/me` command
* Look into bolding and other terminal control features over Telnet. Think about compatability with a client program.
* ~~Add a /quit or /leave command with "reason" parameter.~~
* ~~Store accounts more permanently~~
* ~~Improve username formatting~~
* ~~Broadcast messages when users join and leave~~
* ~~Take another look at the `users` and `connections` dicts - probably some redundancy there~~
* ~~Don't send messages to yourself~~
