Embedthis Appweb Samples
===

These samples are configured to use a locally built Appweb or Appweb installed to the default location
(usually /usr/local/lib/apppweb). To build the samples, you will need to install Appweb and the MakeMe build tool from:

* Appweb - [http://embedthis.com/downloads/appweb/download.ejs](http://embedthis.com/downloads/appweb/download.esp)
* MakeMe - [http://embedthis.com/downloads/makeme/download.ejs](http://embedthis.com/downloads/makeme/download.esp)
* Pak - [http://embedthis.com/downloads/pak/download.ejs](http://embedthis.com/downloads/pak/download.esp)

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

* http://embedthis.com/products/appweb/doc/index.html

Licensing
---

Please see: 

http://embedthis.com/licensing/index.html


Support
---
You have a variety of support choices for Embedthis Software products. You can avail yourself of free support via 
our Online Forum. This is a community based forum where users can share ideas and ask questions. You can also search the
forum for answers to past questions. To visit the Appweb forum, go to:

https://groups.google.com/group/appweb

You also have the option of purchasing support with the Embedthis Commercial License. It includes paid support as 
part of the license benefits.


Copyright
---

Copyright (c) 2003-2014 Embedthis Software, LLC. All Rights Reserved.  Embedthis and Appweb are trademarks of 
Embedthis Software, LLC. Other brands and their products are trademarks of their respective holders.
