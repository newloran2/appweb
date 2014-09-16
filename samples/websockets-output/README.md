ESP WebSockets Sample
===

This sample demonstrates writing large, streaming response without blocking, 
buffering or consuming excessive memory. This sends a large file as a single 
web socket message using multiple frames.

The sample is implemented as an ESP controler with one action. A test web 
page initiates the client WebSocket request to retrieve the file. To run, 
browse to:

    http://localhost:8080/index.html

Requirements
---

* [Appweb](https://embedthis.com/appweb/download.html)
* [MakeMe Build Tool](https://embedthis.com/me/download.html)

To build:
---
    me 

To run:
---
    me run

The server listens on port 8080. Browse to: 
 
     http://localhost:8080/index.html

This opens a web socket and and listens for WebSocket data sent by the server. 
It will display the received data in the browser window.

Code:
---
* [cache](cache) - Directory for compiled ESP modules
* [appweb.conf](appweb.conf) - Appweb server configuration file
* [echo.c](echo.c) - WebSockets echo server code
* [start.me](start.me) - MakeMe build instructions
* [web](web) - Directory containing the index.html web page

Documentation:
---
* [Appweb Documentation](https://embedthis.com/appweb/doc/index.html)
* [ESP Directives](https://embedthis.com/appweb/doc/users/dir/esp.html)
* [ESP Tour](https://embedthis.com/appweb/doc/guide/esp/users/tour.html)
* [ESP Controllers](https://embedthis.com/appweb/doc/guide/esp/users/controllers.html)
* [ESP APIs](https://embedthis.com/appweb/doc/api/esp.html)
* [ESP Guide](https://embedthis.com/appweb/doc/guide/esp/users/index.html)
* [ESP Overview](https://embedthis.com/appweb/doc/guide/esp/users/using.html)

See Also:
---
* [esp-angular-mvc - ESP Angular MVC Application](../esp-angular-mvc/README.md)
* [esp-controller - Serving ESP controllers](../esp-controller/README.md)
* [esp-html-mvc - ESP MVC Application](../esp-html-mvc/README.md)
* [esp-page - Serving ESP pages](../esp-page/README.md)
* [secure-server - Secure server](../secure-server/README.md)
* [simple-server - Simple server and embedding API](../simple-server/README.md)
* [typical-server - Fully featured server and embedding API](../typical-server/README.md)
