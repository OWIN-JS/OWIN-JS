[![OWIN-JS](./owin-js.png)](http://owinjs.org)
## About

OWIN-JS defines a standard framework for REST servers written for io.js, Node.js and application/device logic. It works with both HTTP and COAP servers, and can be a drop-in replacement for existing frameworks such as Connect/Express

OWIN-JS is a superset of the OWIN specifications for HTTP servers, supporting Node.JS enterprise-grade servers, browser-apps, and constained device implementations.

The goal of OWIN-JS is to decouple transport and device logic and, by being an open standard, stimulate the open source ecosystem of Node.js web application/device development tools, without ties to any one framework such as Connect, Express, Koa.js, IIS, node-coap etc. while supporting middleware written for existing frameworks.

OWIN-JS is a port of the [OWIN](http://owin.org) specification, but expands the REST philosophy to web servers, internet of things, etc. 


## Reference Implementations

OWIN-JS is the specification and contains no implementation source code.   However, reference implementations with fully functioning application and server stacks are only one click away:

* [limerun](http://limerun.com) - The reference OWIN-JS implementation for Javascript;  includes a broad ecosystem of HTTP, CoAP, and desktop/mobile embedded server and middleware components (routers, view engines, static asset server, etc.)

* [nodekit.io](http://nodekit.io) - OWIN-JS implementations for OS/X and iOS desktop applications;  contains an embedded lightweight version of Node.js to run anywhere 


## Specifications
[OWIN-JS Specification](./Specification.md)  (this repository)

[Original OWIN Specification for reference](http://owin.org/spec/spec/owin-1.0.0.html) (for .NET only)


## License
Creative Commons Attribution 3.0 Unported License