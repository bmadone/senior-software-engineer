# Network

### Books
1. [Computer Networking](https://eclass.teicrete.gr/modules/document/file.php/TP326/%CE%98%CE%B5%CF%89%CF%81%CE%AF%CE%B1%20(Lectures)/Computer_Networking_A_Top-Down_Approach.pdf)

* OSI Model
    - What is the OSI model?
    - What was it designed for?
    - What levels is it divided into? What does the area of ​​responsibility of each level include?
    - What PDUs are used at each level of the model?
    - How do the levels interact with each other? Does the level know about the availability of other levels (can it contact directly)?
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

        **Resources**

        1. [Talk, Функции уровней модели OSI](https://www.youtube.com/watch?v=7cIC-o2wODs)
        2. [AJAX и COMET, learn js](https://learn.javascript.ru/ajax)
        3. [Using fetch, MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
        4. [HTTP, MDN](https://developer.mozilla.org/ru/docs/Web/HTTP/Overview)
        5. [Что такое HTTP](https://7bloggers.ru/chto-takoe-http/)
