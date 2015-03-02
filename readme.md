[![OWIN-JS](http://owinjs.org/owin-js.png)](http://owinjs.org)

## This Repository

This is the official repository of the OWIN-JS (Open Web Interface for Node.js) Specification. 

Browser the source directories on Github or review formatted online at [owinjs.org](http://owinjs.org)

## About

OWIN-JS defines a standard framework for REST servers for io.js and Node.js.  
It is a port of the [OWIN](http://owin.org) specification, but expands the REST philosophy to web servers, application clients, desktop/mobile apps, etc. 

OWIN-JS is targeted for multiple transport providers including HTTP and COAP servers, and can be a drop-in replacement for existing frameworks such as Connect/Express on Node.js.   It defines a standard way that application/device logic can rely on REST server capabilities without being tied to any one transport (http, express, koa, node-coap, etc.) 

The goal of OWIN-D is to decouple transport and application logic and, by being a free open-source standard (under Creative Commons), stimulate the open source ecosystem of web server development tools, without ties to any one framework such as Connect, Express, Koa.js, IIS, node-coap etc while at the same time being used in commercial applications without restriction.

## Specification
[OWIN-JS Specification](./Specification.md)  (this repository)

We recommend reviewing the [OWIN-D Extension](http://owind.org) and [limerun framework](http://limerun.com) in conjunction with this OWIN-JS specification, so that you get a sense for the implementation possibilities.

## License
Creative Commons Attribution 3.0 Unported License