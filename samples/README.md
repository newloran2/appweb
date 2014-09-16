Embedthis Appweb Samples
===

These samples are configured to use a locally built Appweb or Appweb installed to the default location
(usually /usr/local/lib/apppweb). To build the samples, you will need to install Appweb and the MakeMe build tool from:

* Appweb - [https://embedthis.com/appweb/download.html](https://embedthis.com/appweb/download.html)
* MakeMe - [https://embedthis.com/me/download.html](https://embedthis.com/me/download.html)
* Pak - [https://embedthis.com/pak/download.html](https://embedthis.com/pak/download.html)

The following samples are available:

* [chroot-server](chroot-server/README.md)          Configuring a secure chroot jail for the server.
* [cpp-handler](cpp-handler/README.md)              C++ Handler
* [cpp-module](cpp-module/README.md)                C++ Module
* [deploy-server](deploy-server/README.md)          Deploy Appweb files for copying to a target.
* [max-server](max-server/README.md)                Maximum configuration in appweb.conf.
* [min-server](min-server/README.md)                Minimum configuration in appweb.conf.
* [secure-server](secure-server/README.md)          Secure server using SSL, secure login, chroot and sandbox limits.
* [simple-action](simple-action/README.md)          Action callback. Binding C function to URI.
* [simple-client](simple-client/README.md)          Http client.
* [simple-handler](simple-handler/README.md)        Simple Appweb URL handler.
* [simple-module](simple-module/README.md)          Simple Appweb loadable module.
* [simple-server](simple-server/README.md)          Simple Http server.
* [spy-fliter](spy-filter/README.md)                Simple HTTP pipeline filter.
* [ssl-server](ssl-server/README.md)                SSL server.
* [tiny-server](tiny-server/README.md)              Configure Appweb to be tiny.
* [typical-client](typical-client/README.md)        Using the client HTTP API to retrieve a document.
* [typical-server](typical-server/README.md)        A more fully featured server main program.
* [websockets-echo](websockets-echo/README.md)      WebSockets echo server using an ESP controller.
* [websockets-output](websockets-output/README.md)  Using WebSockets to send a large file.

### Building

To build the samples, see the per-sample README instructions.
To build all, use:

    me --file samples.me  samples

### Documentation

The full product documentation is supplied in HTML format under the doc directory. This is also available online at:

* https://embedthis.com/appweb/doc/index.html

Licensing
---

Please see: 

* https://embedthis.com/licensing/index.html


Support
---
Embedthis provides support for Appweb for commercial customers. If you are interested in commercial support, 
please contact Embedthis at:

* sales@embedthis.com

For non-commercial customers, you may ask questions in the form of well described issues at the:

* [GitHub Ejscript Issue Database](http://github.com/embedthis/ejs/issues)


Copyright
---

Copyright (c) 2003-2014 Embedthis Software, LLC. All Rights Reserved.  Embedthis and Appweb are trademarks of 
Embedthis Software, LLC. Other brands and their products are trademarks of their respective holders.
