---
title:  "This is Data page" 
excerpt: "테스트용"

categories:
  - data
tags:
  - [data, backend]

toc: true
toc_sticky: true
 
date: 2021-10-05
last_modified_at: 2021-10-05
---
Python provides two levels of access to network services. At a low level, you can access the basic socket support in the underlying operating system, which allows you to implement clients and servers for both connection-oriented and connectionless protocols.

Python also has libraries that provide higher-level access to specific application-level network protocols, such as FTP, HTTP, and so on.

This chapter gives you understanding on most famous concept in Networking - Socket Programming.


---
<br>

# What is Sockets?

Sockets are the endpoints of a bidirectional communications channel. Sockets may communicate within a process, between processes on the same machine, or between processes on different continents.

Sockets may be implemented over a number of different channel types: Unix domain sockets, TCP, UDP, and so on. The socket library provides specific classes for handling the common transports as well as a generic interface for handling the rest.

<br>

# The socket Module

To create a socket, you must use the socket.socket() function available in socket module, which has the general syntax −

~~~
s = socket.socket (socket_family, socket_type, protocol=0)
~~~

Here is the description of the parameters −

socket_family − This is either AF_UNIX or AF_INET, as explained earlier.

socket_type − This is either SOCK_STREAM or SOCK_DGRAM.

protocol − This is usually left out, defaulting to 0.

Once you have socket object, then you can use required functions to create your client or server program. Following is the list of functions required −

출처 : https://www.tutorialspoint.com/python/python_networking.htm

[맨 위로 이동하기](#){: .btn .btn--primary }{: .align-right}