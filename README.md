# Awesome WebSockets

A curated list of WebSockets related principles and technologies.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Platforms](#platforms)
- [Runtimes](#runtimes)
- [Service Toolkits](#service-toolkits)
  - [Agnostic](#agnostic)
  - [C](#c)
  - [C++](#c)
  - [D](#d)
  - [Erlang VM](#erlang-vm)
    - [Elixir](#elixir)
    - [Erlang](#erlang)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java VM](#java-vm)
    - [Clojure](#clojure)
    - [Java](#java)
    - [Scala](#scala)
  - [Node.js](#nodejs)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)
- [Capabilities](#capabilities)
  - [API Gateways / Edge Services](#api-gateways--edge-services)
  - [Configuration and Discovery](#configuration-and-discovery)
  - [Security](#security)
  - [Job Schedulers / Workload Automation](#job-schedulers--workload-automation)
  - [Elasticity](#elasticity)
  - [Messaging](#messaging)
  - [Serialization](#serialization)
  - [Storage](#storage)
  - [Reactivity](#reactivity)
  - [Resilience](#resilience)
  - [Testing](#testing)
  - [Monitoring and Debugging](#monitoring-and-debugging)
  - [Logging](#logging)
- [IT Automation / Provisioning](#it-automation--provisioning)
- [Deployment and Continuous Integration](#deployment-and-continuous-integration)
  - [On-prem](#on-prem)
  - [Hosted](#hosted)
  - [Lightweight](#lightweight)
- [Containers](#containers)
- [Documentation & Modeling](#documentation--modeling)
  - [REST APIs](#rest-apis)
- [Standards / Recommendations](#standards--recommendations)
  - [World Wide Web](#world-wide-web)
  - [HTTP/1.1](#http11)
  - [HTTP/2](#http2)
  - [CoAP](#coap)
  - [RPC](#rpc)
  - [Messaging](#messaging-1)
  - [Security](#security-1)
  - [Service Discovery](#service-discovery)
  - [Data Formats](#data-formats)
  - [Vocabularies](#vocabularies)
  - [Unicode](#unicode)
- [Real Life Stories](#real-life-stories)
- [Theory](#theory)
  - [Articles & Papers](#articles--papers)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Sites](#sites)
- [Emerging Technologies](#emerging-technologies)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tools per Language

### Agnostic

- [websocketd](http://websocketd.com/) - WebSockets the UNIX way - Full duplex messaging between web browsers and servers.

### C

- [libwebsockets](https://libwebsockets.org/) - It's a lightweight pure C library built to use minimal CPU and memory resources, and provide fast throughput in both directions as client or server.
- [libwebsock](https://github.com/payden/libwebsock) - C library for easy WebSockets server.
- [Websocket](https://github.com/mortzdk/Websocket) -  A websocket server written in C.

### C++
<!-- #c-1 anchor -->

- [websocketpp](https://github.com/zaphoyd/websocketpp) - C++ websocket client/server library.
- [QtWebSockets](http://wiki.qt.io/QtWebSockets) - The QtWebSockets module is an add-on for the Qt5 library.
- [Beast](https://github.com/vinniefalco/Beast) - HTTP and WebSocket implementations built on Boost.Asio in C++11.

### Erlang

- [sockjs-erlang](https://github.com/sockjs/sockjs-erlang) - WebSocket emulation - Erlang server.
- [Cowboy](https://github.com/ninenines/cowboy) - Small, fast, modular HTTP server written in Erlang.
- [bullet](https://github.com/ninenines/bullet) - Simple, reliable, efficient streaming for Cowboy.

### Go

- [Gorilla Websocket Toolkit](http://www.gorillatoolkit.org/pkg/websocket) - A WebSocket implementation for Go.
- [websocket](https://godoc.org/golang.org/x/net/websocket) - Package websocket implements a client and server for the WebSocket protocol as specified in RFC 6455.

### Java VM

#### Clojure

- [Sente](https://github.com/ptaoussanis/sente) - Realtime web comms for Clojure/Script.
- [Chord](https://github.com/jarohen/chord) - A library designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.
- [Luminusweb](http://www.luminusweb.net/docs/websockets.md) - Luminus is a Clojure micro-framework based on a set of lightweight libraries.

#### Java

- [Project Tyrus](https://tyrus.java.net/) - JSR 356: Java API for WebSocket - Reference Implementation.
- [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) - A barebones WebSocket client and server implementation written in 100% Java.
- [Atmosphere](https://github.com/Atmosphere/atmosphere) - Realtime Client Server Framework for the JVM, supporting WebSockets with Cross-Browser Fallbacks.

#### Scala

- [Play](https://www.playframework.com/documentation/2.5.x/ScalaWebSockets) - The high velocity web framework for Java and Scala.

### Node.js

- [Socket.IO](http://socket.io/) - Featuring the fastest and most reliable real-time engine.
- [Nodejs-websocket](https://github.com/sitegui/nodejs-websocket) - A node.js module for websocket server and client.
- [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) - A WebSocket Implementation for Node.JS (Draft -08 through the final RFC 6455).
- [Sockjs-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server.
- [Ws](https://github.com/websockets/ws) - `ws`: The fastest cross platform RFC-6455 WebSocket implementation for Node.js.

### Perl

- [Net::WebSocket::Server](http://search.cpan.org/~topaz/Net-WebSocket-Server-0.001003/lib/Net/WebSocket/Server.pm) - A straightforward Perl WebSocket server with minimal dependencies.

### PHP

- [Ratchet](http://socketo.me/) - Ratchet is a loosely coupled PHP library providing developers with tools to create real time, bi-directional applications between clients and servers over WebSockets.
- [Php-websocket](https://github.com/nekudo/php-websocket) - A simple PHP WebSocket implementation for PHP 5.3.

### Python

- [Websockets](https://websockets.readthedocs.io) - Websockets is a library for developing WebSocket servers and clients in Python.
- [Ws4py](https://ws4py.readthedocs.io/en/latest/) - A WebSocket package for Python.
- [WebSockets](https://websockets.readthedocs.io/en/stable/) - Python framework for building microservices.

### Ruby

- [Hanami](https://github.com/hanami) - A modern web framework for Ruby.
- [Praxis](https://github.com/rightscale/praxis) - Framework for both designing and implementing APIs.
- [Scorched](https://github.com/wardrop/Scorched) - Light-weight web framework for Ruby.

### Data Formats

- [RFC4627](https://tools.ietf.org/html/rfc4627) - JavaScript Object Notation (JSON).
- [RFC6455](https://tools.ietf.org/html/rfc6455) - The WebSocket Protocol.

## Real Life Stories

- [Clean microservice architecture](http://blog.cleancoder.com/uncle-bob/2014/10/01/CleanMicroserviceArchitecture.html)


## Theory

### Articles & Papers

- [An introduction to Websockets](http://blog.teamtreehouse.com/an-introduction-to-websockets) - A Brief History of Real-Time Web Applications.
- [Introducing WebSockets: Bringing Sockets to the Web](https://www.html5rocks.com/en/tutorials/websockets/basics/) - The Problem: Low Latency Client-Server and Server-Client Connections.
- [About HTML5 WebSocket](https://www.websocket.org/aboutwebsocket.html) - About HTML5 WebSocket.
- [Node.js WebSocket](https://medium.com/@denizozger/finding-the-right-node-js-websocket-implementation-b63bfca0539#.q2313as8p) - Finding the right Node.js WebSocket implementation.
- [Websockets 101](http://lucumr.pocoo.org/2012/9/24/websockets-101/) - Armin Ronacher's Thoughts and Writings (creator of Flask).
- [Real-time Apps](https://www.sitepoint.com/real-time-apps-websockets-server-sent-events/) - Building Real-time Apps with Websockets & Server-Sent Events.


### Talks

- [Initial Steps to Use Websocket-rails](http://tgib23.github.io/blog/2014/08/03/first-post/) - This is the very initial steps to use websocket-rails.

### Tutorials

- [Developing a RESTful Microservice in Python](http://www.skybert.net/python/developing-a-restful-micro-service-in-python/) - A story of how an aging Java project was replaced with a microservice built with Python and Flask.
- [Game On!](https://game-on.org/) - Microservices architecture explained in the context of an old-school text-based adventure game.
- [Microservices without the Servers](https://aws.amazon.com/blogs/compute/microservices-without-the-servers/) - Step by step demo-driven talk about serverless architecture.
- Microservices in C#: [Part 1](http://insidethecpu.com/2015/07/17/microservices-in-c-part-1-building-and-testing/), [Part 2](http://insidethecpu.com/2015/07/31/microservices-in-c-part-2-consistent-message-delivery/), [Part 3](http://insidethecpu.com/2015/08/14/microservices-in-c-part-3-queue-pool-sizing/), [Part 4](http://insidethecpu.com/2015/08/28/microservices-in-c-part-4-scaling-out/), [Part 5](http://insidethecpu.com/2015/09/11/microservices-in-c-part-5-autoscaling/).
- [Microservices with Python, RabbitMQ and Nameko](http://brunorocha.org/python/microservices-with-python-rabbitmq-and-nameko.html)
- [Using Packer and Ansible to build immutable infrastructure](https://blog.codeship.com/packer-ansible/)

### Books

- [WebSocket](http://shop.oreilly.com/product/0636920030485.do) - Lightweight Client-Server Communications. Andrew Lombardi.
- [The Definitive Guide to HTML5 WebSocket](http://dl.finebook.ir/book/6a/10947.pdf) - Build Real-Time Applications with HTML5. By Vanessa Wang, Frank Salim, and Peter Moskovits.
- [Getting Started with HTML5 WebSocket Programming](http://javaarm.com/file/www/html/html5/websocket/books/Packt_Getting.Started.with.HTML5.WebSocket.Programming_Vangos.Pterneas_Aug.2013.pdf) - Develop and deploy your first secure and scalable real-time web application. Vangos Pterneas.

### Sites

- [WebSocket ORG](http://websocket.org/) - The one-stop-shop for all your websocket needs.
- [WebSockets MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) - WebSockets Mozilla Developer Network (MDN).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/facundofarias/awesome-websockets/blob/master/CONTRIBUTING.md) before submitting your suggestion.

Feel free to [open an issue](https://github.com/facundofarias/awesome-websockets/issues) or [create a pull request](https://github.com/facundofarias/awesome-websockets/pulls) with your additions.

:star2: Thank you!

## Acknowledgments

Table of contents generated with [DocToc](https://github.com/thlorenz/doctoc)
