# Awesome WebSockets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of WebSockets related principles and technologies.

[WebSocket](https://en.wikipedia.org/wiki/WebSocket) is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Tools per Language](#tools-per-language)
  - [Agnostic](#agnostic)
  - [C](#c)
  - [C++](#c)
  - [C\# ](#c-1)
  - [Erlang](#erlang)
  - [Go](#go)
  - [Java VM](#java-vm)
    - [Clojure](#clojure)
    - [Java](#java)
    - [Scala](#scala)
  - [Node.js](#nodejs)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)
  - [Protocols and APIs](#protocols-and-apis)
- [Real Life Stories](#real-life-stories)
- [Security](#security)
- [Theory](#theory)
  - [Articles & Papers](#articles--papers)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Sites](#sites)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tools per Language

### Agnostic

- [Websocketd](http://websocketd.com) - WebSockets the UNIX way - Full duplex messaging between web browsers and servers.
- [Nchan](https://nchan.slact.net) - Nchan is a scalable, flexible pub/sub server for the modern web, built as a module for the Nginx web server.
- [Apache-websocket](https://github.com/disconnect/apache-websocket) - Apache WebSocket module.

### C

- [Libwebsockets](http://libwebsockets.org) - It's a lightweight pure C library built to use minimal CPU and memory resources, and provide fast throughput in both directions as client or server.
- [Libwebsock](https://github.com/payden/libwebsock) - C library for easy WebSockets server.
- [Websocket](https://github.com/mortzdk/Websocket) -  Websocket server written in C.

### C++
<!-- #c-1 anchor -->

- [Websocketpp](https://github.com/zaphoyd/websocketpp) - C++ Websocket client/server library.
- [QtWebSockets](http://wiki.qt.io/QtWebSockets) - The QtWebSockets module is an add-on for the Qt5 library.
- [Beast](https://github.com/vinniefalco/Beast) - HTTP and WebSocket implementations built on Boost.Asio in C++11.
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) -  Highly scalable WebSocket server & client library.

### C\#

- [ASP.NET SignalR](http://signalr.net) - Incredibly simple real-time web for .NET.
- [WebSocketListener](http://vtortola.github.io/WebSocketListener) - Lightweight and highly scalable asynchronous WebSocket server for .NET/Mono.

### Erlang

- [Sockjs-erlang](https://github.com/sockjs/sockjs-erlang) - WebSocket emulation - Erlang server.
- [Cowboy](https://github.com/ninenines/cowboy) - Small, fast, modular HTTP server written in Erlang.
- [Bullet](https://github.com/ninenines/bullet) - Simple, reliable, efficient streaming for Cowboy.
- [Kraken](https://github.com/Asana/kraken) - Distributed Pubsub Server for Realtime Apps.

### Go

- [Gorilla Websocket Toolkit](http://www.gorillatoolkit.org/pkg/websocket) - WebSocket implementation for Go.
- [Websocket](https://godoc.org/golang.org/x/net/websocket) - Package Websocket implements a client and server for the WebSocket protocol as specified in RFC 6455.

### Java VM

#### Clojure

- [Sente](https://github.com/ptaoussanis/sente) - Realtime web comms for Clojure/Script.
- [Chord](https://github.com/jarohen/chord) - Library designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.
- [Luminusweb](http://www.luminusweb.net/docs/websockets.md) - Luminus is a Clojure micro-framework based on a set of lightweight libraries.

#### Java

- [Project Tyrus](https://tyrus.java.net/) - JSR 356: Java API for WebSocket - Reference Implementation.
- [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) - Barebones WebSocket client and server implementation written in 100% Java.
- [Atmosphere](https://github.com/Atmosphere/atmosphere) - Realtime Client Server Framework for the JVM, supporting WebSockets with Cross-Browser Fallbacks.
- [Webbit](https://github.com/webbit/webbit) - Java event based WebSocket and HTTP server.

#### Scala

- [Play](https://www.playframework.com/documentation/2.5.x/ScalaWebSockets) - The high velocity web framework for Java and Scala.

### Node.js

- [Socket.IO](http://socket.io/) - Featuring the fastest and most reliable real-time engine.
- [Nodejs-websocket](https://github.com/sitegui/nodejs-websocket) - Node.js module for websocket server and client.
- [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) - WebSocket Implementation for Node.JS (Draft -08 through the final RFC 6455).
- [Sockjs-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server.
- [Ws](https://github.com/websockets/ws) - `ws`: The fastest cross platform RFC-6455 WebSocket implementation for Node.js.
- [deepstream.io](https://deepstream.io/) - Open realtime server a fast, secure and scalable realtime server for mobile, web & iot.

### Perl

- [Net::WebSocket::Server](http://search.cpan.org/~topaz/Net-WebSocket-Server-0.001003/lib/Net/WebSocket/Server.pm) - Straightforward Perl WebSocket server with minimal dependencies.

### PHP

- [Ratchet](http://socketo.me/) - Ratchet is a loosely coupled PHP library providing developers with tools to create real time, bi-directional applications between clients and servers over WebSockets.
- [Php-websocket](https://github.com/nekudo/php-websocket) - Simple PHP WebSocket implementation for PHP 5.3.
- [Phpws](https://github.com/Devristo/phpws) - PHP Web Socket server.

### Python

- [Websockets](https://websockets.readthedocs.io) - Websockets is a library for developing WebSocket servers and clients in Python.
- [Ws4py](https://ws4py.readthedocs.io/en/latest) - WebSocket package for Python.
- [Autobahn.ws](http://autobahn.ws) - Open-source real-time framework for Web, Mobile & Internet of Things.
- [Tornado](http://www.tornadoweb.org/) - Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed.

### Ruby

- [Em-websocket](https://github.com/igrigorik/em-websocket) - EventMachine based WebSocket server.
- [Faye-websocket-ruby](https://github.com/faye/faye-websocket-ruby) - Standards-compliant WebSocket client and server.
- [Websocket-driver-ruby](https://github.com/faye/websocket-driver-ruby) - WebSocket protocol handler with pluggable I/O.
- [Websocket-ruby](https://github.com/imanel/websocket-ruby) - Universal Ruby library to handle WebSocket protocol.
- [Scorched](https://github.com/wardrop/Scorched) - Light-weight web framework for Ruby.
- [Firehose](http://firehose.io/) - Build realtime Ruby web applications. Created by the fine folks at Poll Everywhere.

### Protocols and APIs

- [RFC6455](https://tools.ietf.org/html/rfc6455) - The WebSocket Protocol.
- [The WebSocket API](https://www.w3.org/TR/websockets/) - The W3C The WebSocket API.
- [Hixie76](https://tools.ietf.org/html/draft-hixie-thewebsocketprotocol-76) - The WebSocket protocol draft-hixie-thewebsocketprotocol-76

## Real Life Stories

- [The top 10 realtime web apps](http://www.creativebloq.com/app-design/top-10-realtime-web-apps-5133752)
- [Super sync sports](https://blog.chromium.org/2013/02/on-track-with-chrome-super-sync-sports.html)
- [Firepad](https://firepad.io)
- [JabbR](http://about.jabbr.net/)
- [Kaazing](https://kaazing.com/)

## Security

- [WebSockets - An Introduction](https://gist.github.com/subudeepak/9897212) - The problems and some security implications of websockets - Cross-site WebSockets Scripting (XSWS).
- [Hacking with WebSockets](https://media.blackhat.com/bh-us-12/Briefings/Shekyan/BH_US_12_Shekyan_Toukharian_Hacking_Websocket_Slides.pdf) - Talk on Blackhat USA 2012 Conference.
- [Testing WebSockets](https://www.owasp.org/index.php/Testing_WebSockets_(OTG-CLIENT-010)) - This article is part of the new OWASP Testing Guide v4.
- [Websockets Auth](http://stratumsecurity.ghost.io/2016/06/13/websockets-auth) - Journey into WebSockets Authentication/Authorization.
- [Kaazing](https://kaazing.com/2012/02/28/html5-websocket-security-is-strong) - HTML5 WebSocket Security is Strong.


## Theory

### Articles & Papers

- [An introduction to Websockets](http://blog.teamtreehouse.com/an-introduction-to-websockets) - Brief History of Real-Time Web Applications.
- [Introducing WebSockets: Bringing Sockets to the Web](https://www.html5rocks.com/en/tutorials/websockets/basics/) - The Problem: Low Latency Client-Server and Server-Client Connections.
- [About HTML5 WebSocket](https://www.websocket.org/aboutwebsocket.html) - About HTML5 WebSocket.
- [Node.js WebSocket](https://medium.com/@denizozger/finding-the-right-node-js-websocket-implementation-b63bfca0539#.q2313as8p) - Finding the right Node.js WebSocket implementation.
- [Websockets 101](http://lucumr.pocoo.org/2012/9/24/websockets-101/) - Armin Ronacher's Thoughts and Writings (creator of Flask).
- [Real-time Apps](https://www.sitepoint.com/real-time-apps-websockets-server-sent-events/) - Building Real-time Apps with Websockets & Server-Sent Events.
- [Real-Time Web by Paul Banks](https://banksco.de/p/state-of-realtime-web-2016.html) - The State of Real-Time Web in 2016.
- [Are WebSockets the future?](https://samsaffron.com/archive/2015/12/29/websockets-caution-required) - WebSockets, caution required!
- [MSDN Microsoft Blog](https://msdn.microsoft.com/en-us/hh563510.aspx) - The Dangers of HTML5: WebSockets and Stable Standards.
- [Webpush Internet-Draft](https://martinthomson.github.io/drafts/draft-thomson-webpush-http2.html) - Generic Event Delivery Using HTTP Push.

### Talks

- [Initial Steps to Use Websocket-rails](http://tgib23.github.io/blog/2014/08/03/first-post/) - This is the very initial steps to use websocket-rails.

### Tutorials

- [Honeybadger.IO](http://blog.honeybadger.io/building-a-simple-websockets-server-from-scratch-in-ruby) - Building a simple websockets server from scratch in Ruby.
- [Engineyard](https://blog.engineyard.com/2013/getting-started-with-ruby-and-websockets) - Getting Started with Ruby and WebSockets.


### Books

- [WebSocket](http://shop.oreilly.com/product/0636920030485.do) - Lightweight Client-Server Communications. Andrew Lombardi.
- [The Definitive Guide to HTML5 WebSocket](http://dl.finebook.ir/book/6a/10947.pdf) - Build Real-Time Applications with HTML5. By Vanessa Wang, Frank Salim, and Peter Moskovits.
- [Getting Started with HTML5 WebSocket Programming](http://javaarm.com/file/www/html/html5/websocket/books/Packt_Getting.Started.with.HTML5.WebSocket.Programming_Vangos.Pterneas_Aug.2013.pdf) - Develop and deploy your first secure and scalable real-time web application. Vangos Pterneas.

### Sites

- [WebSocket ORG](http://websocket.org) - The one-stop-shop for all your websocket needs.
- [WebSockets MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) - WebSockets Mozilla Developer Network (MDN).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/facundofarias/awesome-websockets/blob/master/CONTRIBUTING.md) before submitting your suggestion.

Feel free to [open an issue](https://github.com/facundofarias/awesome-websockets/issues) or [create a pull request](https://github.com/facundofarias/awesome-websockets/pulls) with your additions.

Thanks!

## Acknowledgments

Table of contents generated with [DocToc](https://github.com/thlorenz/doctoc)
