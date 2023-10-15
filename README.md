# BHP-Inspired-Python
### Python scripts inspired by the book "Black Hat Python" 

1. [TCP client](https://github.com/MRCyberBlog/BHP-Inspired-Python/blob/main/tcp-client.py) script inspired from BHP book.
   1. Added arguments, error handling, ssl, input validation, etc
   2. Planning to add UDP capabilities to this script, which will cover the UDP script in BHP.

2. [TCP-UDP-client](https://github.com/MRCyberBlog/BHP-Inspired-Python/blob/main/TCP-UDP-client.py) script is an updated version of the previously made TCP-client script but includes:
   1. UDP capability added.
   2. Removal of 443 if condition so -s, -ssl option is required if running on any port requiring it.
   3. Force requirements of hostname/IP and port number.
   4. Optional arguments: -u, -UDP and -s, -ssl.