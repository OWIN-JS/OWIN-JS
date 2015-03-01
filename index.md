[![OWIN-JS](./owin-js.png)](http://owinjs.org)
## About

This is the official repository of the OWIN-JS (Open Web Interface for Node.js) Specification. 

OWIN-JS defines a standard framework for REST servers for io.js and Node.js.  
It is a port of the [OWIN](http://owin.org) specification, but expands the REST philosophy to web servers, application clients, desktop/mobile apps, etc. 

OWIN-JS is targeted for multiple transport providers including HTTP and COAP servers, and can be a drop-in replacement for existing frameworks such as Connect/Express on Node.js.   It defines a standard way that application/device logic can rely on REST server capabilities without being tied to any one transport (http, express, koa, node-coap, etc.) 

The goal of OWIN-D is to decouple transport and application logic and, by being a free open-source standard (under Creative Commons), stimulate the open source ecosystem of web server development tools, without ties to any one framework such as Connect, Express, Koa.js, IIS, node-coap etc while at the same time being used in commercial applications without restriction.

## Reference Implementations

OWIN-JS is the specification and contains no implementation source code.   However, reference implementations with fully functioning application and server stacks are only one click away:

* [limerun](http://limerun.com) - The reference OWIN-JS implementation for Javascript;  includes a broad ecosystem of HTTP, CoAP, and desktop/mobile embedded server and middleware components (routers, view engines, static asset server, etc.)

* [nodekit.io](http://nodekit.io) - OWIN-JS implementations for OS/X and iOS desktop applications;  contains an embedded lightweight fork of Node.js to run anywhere 


## Specifications
[OWIN-JS Specification](./Specification.md)  (this repository)

[OWIN-D Specification](./Specification.md) (Extends OWIN-JS for Networked Devices and Internet of Things) 

[Original OWIN Specification for reference](http://owin.org/spec/spec/owin-1.0.0.html) (for .NET only)


## License
Creative Commons Attribution 3.0 Unported License