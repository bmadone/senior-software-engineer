# Network

## Questions
* OSI Model
    - What is the OSI model?
    - What was it designed for?
    - What levels is it divided into? What does the area of ​​responsibility of each level include?
    - What PDUs are used at each level of the model?
    - How do the levels interact with each other? Does the level know about the availability of other levels (can it contact directly)?
    - What layers are represented in OSI and in TCP/IP models?
* Transport Protocols
    - What is a unicast message (unicast)?
    - What is broadcast transmission?
    - What is TCP? How does he work?
    - What is multiplexing?
    - What is UDP? How does he work?
    - What is the difference between TCP and UDP?
    - In which case is it preferable to use TCP, and in which UDP?
* HTTP
    - What is HTTP?
    - What are the parts of an HTTP message?
    - What are the main methods of the protocol? What does each of them do?
    - What are the HTTP response status codes for? What sublevels are status codes divided into?
    - What is a client-server protocol?
    - What is a user agent?
    - What is a proxy?
    - What is the difference between HTTP 1.1, HTTP 2 and HTTPS?
    - Is it possible to control the state in HTTP?
    - What are sessions?
* TCP/IP protocol stack:
  * DNS
    * What is Domain Name system? DNS terminology.
    * How it works?
  * HTTP
    * Request (methods, headers, query, body).
    * Response (status codes, headers, body).
  * TCP
    * How does TCP operate? How does it open and close a connection?
    * How does UDP operate?
    * How do UDP and TCP differ? When is it better to choose using TCP over UDP and vice versa?
    * What are the functions of TCP/IP transport layer?
    * What is IPv4 socket?
    * What protocols operate at a transport layer?
  * IP
    * What are the types of IP addresses and how do they differ?
    * What are the parts of IP address?
    * What is a subnet mask?
    * What is a network interface? Which parameters do define a network interface?
    * How to show interfaces list in Linux?
    * What is the purpose of using `lo`, `eth` and `wlan` interfaces?
    * How does addressing an interface differ in a local and in a global networks?
    * What are REST basic principles?
* Sockets
    - What is a socket in the context of networks?
    - Why is a socket considered an abstract object?
    - What is unix domain socket?
* Communication with the server
    - What are AJAX and COMET?
    - What is XMLHttpRequest?
        - What data can work with?
        - What protocols are used with?
        - Is it possible to send a request synchronously?
        - Is it possible to limit the duration of the request?
        - How to renew an interrupted request?
    - What is polling and long polling?
    - What is a WebSocket?
        - What is this technology used for?
        - What are the differences from unix domain socket?
        - What protocol is the data sent to? How does he work?
        - What is a websocket frame? How do they work and what types exist?
        - In what cases will the socket connection be closed?
        - How to resume a broken connection? How to restore file download from the same place where the connection was interrupted?
        - What is PING / PONG?
        - What are the alternatives if this technology is not supported by the browser?
    - What is Server-Side Events?
        - What are the differences from WebSockets?
        - What protocol is the data transferred to?
        - In what format does the server send messages?
        - How does the connection to the server resume if it was lost? How to resume connection from the last received message?
        - What are the events of Server-Side Events? Can I create custom events?
    - How does the `fetch` method work in JavaScript?
        - How to set options and headers to the request object?
        - What are the differences from XMLHttpRequest?
        - How to send / receive cookies with `fetch`?
        - What status does he set for the 400th and 500th mistakes?
        - Why is the `ok` property used in the response?
    - What is JSONP for?
        - How to process the response from the server?
        - How to catch and process errors?
        - How to implement COMET functionality using JSONP?
