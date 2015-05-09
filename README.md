# show-lost
A command-line tool for linux to show and graph packet lost in ping responses or SYN-ACK responses.

# Usage
./show-lost [ -h <host> -p <port> | -h <host> ]
     -p <port>    Show SYN-ACK losts for SYN ping to <port>. (<host> is required. Must be super-user.)
     -h <host>    Ping target HOSTess. (Default is 8.8.8.8)
     -H           Show help


# Build deb package
$ debuild -us -uc -b

