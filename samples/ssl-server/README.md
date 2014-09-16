SSL Server Sample
===

This sample shows how to configure Appweb to use SSL.

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

The server listens on port 4443 for SSL requests. Browse to: 
 
     https://localhost:4443/

Code:
---
* [appweb.conf](appweb.conf) - Appweb server configuration file
* [self.crt](self.crt) - Self-signed test certificate
* [self.key](self.key) - Test private key
* [web](web) - Web content to serve
* [start.me](start.me) - MakeMe build instructions

Documentation:
---
* [Appweb Documentation](https://embedthis.com/appweb/doc/index.html)
* [Configuration Directives](https://embedthis.com/appweb/doc/users/configuration.html#directives)
* [Security Considerations](https://embedthis.com/appweb/doc/users/security.html)
* [SSL in Appweb](https://embedthis.com/appweb/doc/users/ssl.html)

See Also:
---
* [min-server - Minimal server configuration](../min-server/README.md)
* [secure-server - Secure server configuration](../secure-server/README.md)
* [simple-server - Simple one-line embedding API](../simple-server/README.md)
