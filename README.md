# Awesome WebSockets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of WebSockets related principles and technologies.

[WebSocket](https://en.wikipedia.org/wiki/WebSocket) is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Tools per Language](#tools-per-language)
  - [Agnostic](#agnostic)
  - [Ballerina](#ballerina)
  - [C](#c)
  - [C++](#c-1)
  - [C\#](#c-2)
  - [D](#d)
  - [Elixir](#elixir)
  - [Erlang](#erlang)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java VM](#java-vm)
    - [Clojure](#clojure)
    - [Java](#java)
    - [Kotlin](#kotlin)
    - [Scala](#scala)
  - [Julia](#julia)
  - [Node.js / JavaScript](#nodejs--javascript)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Swift](#swift)
  - [Protocols and APIs](#protocols-and-apis)
- [Managed / Hosted Services](#managed--hosted-services)
- [GUI Testing Tools](#gui-testing-tools)
- [Browser libraries](#browser-libraries)
- [Visualization Tools](#visualization-tools)
- [Command-Line Interface (CLI) Tools](#command-line-interface-cli-tools)
- [Real Life Stories](#real-life-stories)
- [Security](#security)
- [Theory](#theory)
  - [Articles & Papers](#articles--papers)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Sites](#sites)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tools per Language

### Agnostic

- [Centrifugo](https://github.com/centrifugal/centrifugo) - Scalable real-time messaging in language-agnostic way.
- [Websocketd](http://websocketd.com) - WebSockets the UNIX way - Full duplex messaging between web browsers and servers.
- [Nchan](https://nchan.slact.net) - Nchan is a scalable, flexible pub/sub server for the modern web, built as a module for the Nginx web server.
- [Apache-websocket](https://github.com/disconnect/apache-websocket) - Apache WebSocket module.
- [MinnowServer](https://github.com/RealTimeLogic/MinnowServer) - A super small and fast embedded HTTP(S) WebSocket server.
- [gwsocket](https://github.com/allinurl/gwsocket) - Fast, standalone, language-agnostic WebSocket server RFC6455 compliant.

### Ballerina

- [Ballerina WebSocket Module](https://lib.ballerina.io/ballerina/websocket/latest) - Tailored WebSocket client and server implementations in Ballerina, designed and optimized for seamless integration.

### C

- [Libwebsockets](https://libwebsockets.org) - It's a lightweight pure C library built to use minimal CPU and memory resources, and provide fast throughput in both directions as client or server.
- [civetweb](https://github.com/civetweb/civetweb) - Embedded C/C++ web server with WebSocket client and server support, easy to integrate.
- [Websocket](https://github.com/mortzdk/Websocket) -  Websocket server written in C.
- [facil.io](http://facil.io) - A server/framework library for web applications, including Websockets and native pub/sub.
- [libuwsc](https://github.com/zhaojh329/libuwsc) - A Lightweight and fully asynchronous WebSocket client C library based on libubox for Embedded Linux.
- [mongoose](https://github.com/cesanta/mongoose) - Mongoose Embedded Web Server Library - Mongoose is more than an embedded webserver. It is a multi-protocol embedded networking library with functions including TCP, HTTP client and server, WebSocket client and server, MQTT client and broker and much more.
- [WebSockets in C](https://github.com/cjhdev/wic) - A minimal implementation for embedded applications.
- [Wslay](https://github.com/tatsuhiro-t/wslay) - Designed to be embedded in other programs; freedom to choose your own network I/O. Event-based API, as well as synchronous frame-based.

### C++
<!-- #c-1 anchor -->

- [Websocketpp](https://github.com/zaphoyd/websocketpp) - C++ Websocket client/server library.
- [QtWebSockets](http://wiki.qt.io/QtWebSockets) - The QtWebSockets module is an add-on for the Qt5 library.
- [Beast](https://github.com/boostorg/beast) - HTTP and WebSocket built on Boost.Asio in C++11.
- [µWebSockets](https://github.com/uNetworking/uWebSockets) -  Highly scalable WebSocket server library.
- [Simple-WebSocket-Server](https://github.com/eidheim/Simple-WebSocket-Server) -  A very simple, fast, multithreaded, platform independent WebSocket (WS) and WebSocket Secure (WSS) server and client library implemented using C++11, Boost.Asio and OpenSSL.
- [IXWebSocket](https://github.com/machinezone/IXWebSocket) - Lightweight C++11 multi-threaded client library with TLS support.
- [LAppS](https://github.com/ITpC/LAppS) - LAppS - Lua Application Server for micro-services with default communication over WebSockets.
- [libhv](https://github.com/ithewei/libhv) - A network library for developing TCP/UDP/SSL/HTTP/WebSocket client/server.
- [Drogon](https://github.com/an-tao/drogon) - Fast C++14/17/20 HTTP application framework with built-in WebSocket controllers.
- [Crow](https://github.com/CrowCpp/Crow) - Fast and easy-to-use C++ microframework for the web, with WebSocket support.
- [Oat++](https://github.com/oatpp/oatpp) - Light and powerful C++ web framework with async WebSocket support and zero dependencies.
- [POCO](https://github.com/pocoproject/poco) - C++ libraries for network-centric applications, including HTTP and WebSocket classes.

### C\#
<!-- #c-2 anchor -->

- [ASP.NET SignalR](http://signalr.net) - Incredibly simple real-time web for .NET.
- [WebSocketListener](http://vtortola.github.io/WebSocketListener) - Lightweight and highly scalable asynchronous WebSocket server for .NET/Mono.
- [websocket-rpc](https://github.com/dajuric/websocket-rpc) - WebSocket RPC library for .NET with auto JavaScript client code generation, supporting ASP.NET Core.
- [NetGain](https://github.com/StackExchange/NetGain) - A high performance websocket server library powering Stack Overflow.
- [websocket-manager](https://github.com/radu-matei/websocket-manager) - Real-Time library for ASP .NET Core.
- [WebSockets](https://github.com/aspnet/WebSockets) - Implementation of the WebSocket protocol, along with client and server integration components.
- [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-2.1) - This article explains how to get started with WebSockets in ASP.NET Core.
- [unity-websocket-server](https://github.com/shaunabanana/unity-websocket-server) - A simple, zero-dependency WebSocket server for Unity.
- [websocket-sharp](https://github.com/sta/websocket-sharp) - A C# implementation of the WebSocket protocol client and server.
- [websocket-client](https://github.com/Marfusios/websocket-client) - Reactive, reconnecting WebSocket client for .NET based on System.Net.WebSockets.
- [Ninja.WebSockets](https://github.com/ninjasource/Ninja.WebSockets) - Standalone, high-performance C# WebSocket client and server implementation.
- [Fleck](https://github.com/statianzo/Fleck) - Simple C# WebSocket server implementation with no dependencies.

### D

- [Arsd:CGI](https://github.com/adamdruppe/arsd) - Uniform server-side API for CGI, FastCGI, SCGI, and HTTP web applications. Offers both lower- and higher- level api options among other common (optional) things like websocket and event source serving support.
- [Handy](https://github.com/andrewlalis/handy-httpd) - The simplest HTTP server for your D project.
- [Lighttp](https://github.com/Kripth/lighttp) - Lightweight asynchronous HTTP and WebSocket server library for the D.
- [Serverino](https://github.com/trikko/serverino) - Small and ready-to-go http server. Support for websockets included.
- [Vibe.d](https://github.com/vibe-d/vibe.d) - High-performance asynchronous I/O, concurrency and web application toolkit written in D.
- [Websocketd](https://github.com/o3o/websocketd) - A websocket server in D.

### Elixir

- [Phoenix](https://github.com/phoenixframework/phoenix) - Productive Elixir web framework with Channels for realtime, scalable WebSocket communication.
- [Phoenix LiveView](https://github.com/phoenixframework/phoenix_live_view) - Rich, realtime server-rendered UIs over WebSockets without writing JavaScript.
- [Bandit](https://github.com/mtrudel/bandit) - Pure-Elixir HTTP and WebSocket server built for Plug and WebSock.
- [WebSockex](https://github.com/Azolo/websockex) - Elixir WebSocket client library built on top of GenServer.

### Erlang

- [Sockjs-erlang](https://github.com/sockjs/sockjs-erlang) - WebSocket emulation - Erlang server.
- [Cowboy](https://github.com/ninenines/cowboy) - Small, fast, modular HTTP server written in Erlang.
- [n2o](https://github.com/synrc/n2o) - Erlang web server on websockets.
- [Kraken](https://github.com/Asana/kraken) - Distributed Pubsub Server for Realtime Apps.
- [Gun](https://github.com/ninenines/gun) - Erlang HTTP/1.1, HTTP/2 and WebSocket client library.

### Go

- [Gorilla Websocket](https://github.com/gorilla/websocket) - WebSocket implementation for Go.
- [Websocket](https://godoc.org/golang.org/x/net/websocket) - Package Websocket implements a client and server for the WebSocket protocol as specified in RFC 6455.
- [Ws](https://github.com/gobwas/ws) - Tiny WebSocket library for Go.
- [1m-go-websockets](https://github.com/eranyanay/1m-go-websockets) - Handling 1M websockets connections in Go.
- [gotify/server](https://gotify.net/) - A simple server for sending and receiving messages in real-time per web socket.
- [coder/websocket](https://github.com/coder/websocket) - A minimal and idiomatic WebSocket library for Go (formerly nhooyr/websocket).
- [Centrifuge](https://github.com/centrifugal/centrifuge) - Real-time messaging library for Go with scalability in mind.
- [GWS](https://github.com/lxzan/gws) - Simple, fast, reliable websocket server & client, supports running over tcp/kcp/unix domain socket.
- [Velaros](https://github.com/RobertWHurst/Velaros) - A lightweight framework with HTTP-style routing, bidirectional messaging, and middleware.
- [KubeStellar Console](https://github.com/kubestellar/console) - AI-powered multi-cluster Kubernetes dashboard using WebSockets for real-time cluster communication and live observability streams.
- [Melody](https://github.com/olahol/melody) - Minimalist framework for dealing with WebSocket sessions, including broadcasting and message buffering.
- [Fiber WebSocket](https://github.com/gofiber/websocket) - WebSocket middleware for the Fiber web framework, built on Fasthttp.
- [nbio](https://github.com/lesismal/nbio) - Non-blocking, event-driven networking framework with high-performance WebSocket support and low memory usage.
- [greatws](https://github.com/antlabs/greatws) - Event-driven WebSocket server able to handle millions of connections with low memory.
- [go-socket.io](https://github.com/googollee/go-socket.io) - Socket.IO library for Go, a realtime application framework.

### Haskell

- [Websockets](https://github.com/jaspervdj/websockets) - A Haskell library for creating WebSocket-capable servers.
- [n2o](https://github.com/o3/n2o) - Haskell implementation of Erlang's n2o - web server on websockets.

### Java VM

#### Clojure

- [Sente](https://github.com/ptaoussanis/sente) - Realtime web comms for Clojure/Script.
- [Chord](https://github.com/jarohen/chord) - Library designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.
- [Luminusweb](http://www.luminusweb.net/docs/websockets.md) - Luminus is a Clojure micro-framework based on a set of lightweight libraries.
- [http-kit](https://github.com/http-kit/http-kit) - Minimalist, high-performance HTTP server and client with async WebSocket support.

#### Java

- [Project Tyrus](https://github.com/eclipse-ee4j/tyrus) - JSR 356: Java API for WebSocket - Reference Implementation.
- [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) - Barebones WebSocket client and server implementation written in 100% Java.
- [Atmosphere](https://github.com/Atmosphere/atmosphere) - Realtime Client Server Framework for the JVM, supporting WebSockets with Cross-Browser Fallbacks.
- [Webbit](https://github.com/webbit/webbit) - Java event based WebSocket and HTTP server.
- [nv-websocket-client](https://github.com/TakahikoKawasaki/nv-websocket-client) - High-quality WebSocket client implementation in Java which.
- [Netty](https://github.com/netty/netty) - Asynchronous event-driven network framework with full WebSocket codec support.
- [Vert.x](https://github.com/eclipse-vertx/vert.x) - Reactive, polyglot toolkit for the JVM with first-class WebSocket client and server APIs.
- [Undertow](https://github.com/undertow-io/undertow) - High-performance web server (WildFly's core) with a dedicated WebSocket API.
- [Javalin](https://github.com/javalin/javalin) - Lightweight web framework for Java and Kotlin with simple WebSocket handlers.

#### Kotlin

- [Scarlet](https://github.com/Tinder/Scarlet) - Tinder's Retrofit inspired WebSocket client for Kotlin, Java, and Android.
- [Ktor](https://github.com/ktorio/ktor) - JetBrains' Kotlin async framework with built-in WebSocket client and server support.
- [OkHttp](https://github.com/square/okhttp) - HTTP client for the JVM and Android with a robust WebSocket client.

#### Scala

- [Play](https://www.playframework.com/documentation/2.5.x/ScalaWebSockets) - The high velocity web framework for Java and Scala.
- [Finagle-websocket](https://github.com/finagle/finagle-websocket) - Finagle Websocket clients and servers.
- [http4s](https://github.com/http4s/http4s) - Typeful, functional, streaming HTTP for Scala with WebSocket support.
- [Apache Pekko HTTP](https://github.com/apache/pekko-http) - Streaming WebSocket client and server directives; the Apache-licensed Akka HTTP fork.
- [ZIO HTTP](https://github.com/zio/zio-http) - High-performance, functional Scala HTTP library with WebSocket support built on ZIO.


### Julia

- [HTTP.jl](https://github.com/JuliaWeb/HTTP.jl) - HTTP library for Julia with support on Websockets.
- [WebSockets.jl](https://github.com/JuliaWeb/WebSockets.jl) - A WebSockets library for Julia.

### Node.js / JavaScript

- [Socket.IO](http://socket.io/) - Featuring the fastest and most reliable real-time engine.
- [Nodejs-websocket](https://github.com/sitegui/nodejs-websocket) - Node.js module for websocket server and client.
- [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) - WebSocket Implementation for Node.JS (Draft -08 through the final RFC 6455).
- [Sockjs-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server.
- [Ws](https://github.com/websockets/ws) - `ws`: The fastest cross platform RFC-6455 WebSocket implementation for Node.js.
- [deepstream.io](https://deepstream.io/) - Open realtime server a fast, secure and scalable realtime server for mobile, web & iot.
- [websocket-as-promised](https://github.com/vitalets/websocket-as-promised) - Promise-based W3C WebSocket wrapper: allows to use promises when connecting, disconnecting and messaging with WebSocket server.
- [faye-websocket-node](https://github.com/faye/faye-websocket-node) - Standards-compliant WebSocket client and server.
- [ws-wrapper](https://github.com/bminer/ws-wrapper) - Lightweight WebSocket wrapper that provides a socket.io-like event-handler API along with Promise-based requests.
- [ws-server-wrapper](https://github.com/bminer/ws-server-wrapper) - Companion library for ws-wrapper for the server-side.
- [wspromisify](https://www.npmjs.com/package/wspromisify) - Makes WebSockets async/await ready with a lot of yummies.
- [uws](https://github.com/uNetworking/uWebSockets.js) - Tiny WebSockets (access to the C++ library, µWebSockets, via Node.js)
- [netflux](https://coast-team.github.io/netflux/) - JavaScript client and server side transport API based on WebRTC & WebSocket
- [Sockette](https://github.com/lukeed/sockette) - WebSocket client that will automatically reconnect if the connection is lost.
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets for Node.js and JavaScript/TypeScript.
- [soketi](https://github.com/soketi/soketi) - Just another simple, fast, and resilient open-source WebSockets server. Built on top of uWebSockets.js.
- [ZilaWS Server](https://zilaws.com) - A very easy-to-use and fast WS implementation with async/await eventhandlers and extendable classes.
- [graphql-ws](https://github.com/enisdenjo/graphql-ws) - Coherent, zero-dependency, spec-compliant GraphQL over WebSocket server and client.
- [y-websocket](https://github.com/yjs/y-websocket) - WebSocket connection provider for Yjs, enabling real-time collaborative editing and CRDT sync.
- [Bun WebSockets](https://bun.sh/docs/api/websockets) - Native high-performance WebSocket server built into the Bun runtime with pub/sub support.
- [Hono WebSocket Helper](https://hono.dev/docs/helpers/websocket) - Built-in WebSocket helper for the Hono framework across Cloudflare Workers, Bun, Deno, and Node.js.
- [tRPC Subscriptions](https://trpc.io/docs/server/subscriptions) - End-to-end typesafe real-time subscriptions over WebSockets for TypeScript apps.
- [PartySocket](https://github.com/partykit/partykit/tree/main/packages/partysocket) - Robust WebSocket client with automatic reconnection and buffering, usable against any WS server.

### Perl

- [`Net::WebSocket::Server`](https://metacpan.org/pod/Net::WebSocket::Server) - Straightforward Perl WebSocket server with minimal dependencies.
- [`AnyEvent::WebSocket::Server`](https://metacpan.org/pod/AnyEvent::WebSocket::Server) - WebSocket server for AnyEvent
- [`Mojolicious`](https://metacpan.org/pod/distribution/Mojolicious/lib/Mojolicious/Guides/Routing.pod#WebSockets) - An amazing real-time web framework built on top of the powerful Mojo web development toolkit and comes with websockets built in. 
- [`Dancer2::Plugin::WebSocket`](https://metacpan.org/pod/Dancer2::Plugin::WebSocket) - add a websocket interface to your Dancer2 app
- [`Plack::App::WebSocket`](https://metacpan.org/pod/Plack::App::WebSocket) - WebSocket server as a plack/PSGI application
- [`Net::WebSocket`](https://metacpan.org/pod/Net::WebSocket::Server) - Super-flexible, minimal client & server library

### PHP

- [Ratchet](http://socketo.me/) - Ratchet is a loosely coupled PHP library providing developers with tools to create real time, bi-directional applications between clients and servers over WebSockets.
- [Php-websocket](https://github.com/nekudo/php-websocket) - Simple PHP WebSocket implementation for PHP 5.3.
- [Phpws](https://github.com/Devristo/phpws) - PHP Web Socket server.
- [Sandstone](https://eole-io.github.io/sandstone/) - Microframework to build a real time Rest API.
- [Laravel Websockets](https://github.com/beyondcode/laravel-websockets) - A package for Laravel 5.7 and up that will get your application started with WebSockets in no-time!

### Python

- [Django Channels](https://channels.readthedocs.io/en/latest) - Extends [Django](https://www.djangoproject.com/) with  WebSocket, long-poll HTTP, task offloading and other async support.
- [Websockets](https://websockets.readthedocs.io) ([code](https://github.com/aaugustin/websockets)) - Websockets is a library for developing WebSocket servers and clients in Python 3.
- [Ws4py](https://ws4py.readthedocs.io/en/latest) - WebSocket package for Python.
- [Autobahn.ws](https://github.com/crossbario/autobahn-python) - Open-source real-time framework for Web, Mobile & Internet of Things.
- [Tornado](http://www.tornadoweb.org/) - Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed.
- [WebSocket Benchmarker](https://github.com/healeycodes/websocket-benchmarker) - CLI tool for benchmarking WebSocket Servers.
- [Starlette](https://www.starlette.io/websockets/)
- [Simple Http Server](https://github.com/keijack/python-simple-http-server) A simple HTTP server, including support of numerous websocket events like `on_text_message`, `on_binary_message` etc. And even `on_binary_frame`.
- [Picows](https://picows.readthedocs.io/en/stable/) - Ultra-fast WebSocket client and server library for asyncio.
- [WebRockets](https://github.com/ploMP4/webrockets) - Rust-powered WebSocket server with Django integration, message pattern matching, Pydantic validation, and more.
- [python-socketio](https://github.com/miguelgrinberg/python-socketio) - Python implementation of the Socket.IO realtime client and server.
- [simple-websocket](https://github.com/miguelgrinberg/simple-websocket) - Simple WebSocket server and client for Python built on WSGI/ASGI.
- [Socketify.py](https://github.com/cirospaciari/socketify.py) - Fast WebSocket and HTTP server for Python built on uWebSockets, with ASGI/WSGI support.
- [python-websocket-server](https://github.com/Pithikos/python-websocket-server) - Minimal, dependency-free WebSocket server written in pure Python.
- [websocket-client](https://github.com/websocket-client/websocket-client) - Popular, long-standing synchronous client for Python.

### R

- [httpuv](https://cran.r-project.org/package=httpuv) - Provides low-level socket and protocol support for WebSocket (and HTTP) servers in R. Built on top of the [libuv](https://github.com/libuv/libuv) and [http-parser](https://github.com/nodejs/http-parser) C libraries.
- [routr](https://cran.r-project.org/package=routr) - A simple router for WebSocket (and HTTP) requests in R.
- [websocket](https://cran.r-project.org/package=websocket) - Provides a WebSocket client interface for R.

### Ruby

- [AnyCable](http://anycable.io/) - Polyglot replacement for Ruby WebSocket servers with Action Cable protocol.
- [Em-websocket](https://github.com/igrigorik/em-websocket) - EventMachine based WebSocket server.
- [Faye-websocket-ruby](https://github.com/faye/faye-websocket-ruby) - Standards-compliant WebSocket client and server.
- [Iodine](https://github.com/boazsegev/iodine) - WebSocket/HTTP server with integrated pub/sub and optional Redis support.
- [Rage](https://github.com/rage-rb/rage) - Fast WebSocket server compatible with Action Cable.
- [Websocket-driver-ruby](https://github.com/faye/websocket-driver-ruby) - WebSocket protocol handler with pluggable I/O.
- [Websocket-ruby](https://github.com/imanel/websocket-ruby) - Universal Ruby library to handle WebSocket protocol.
- [Scorched](https://github.com/wardrop/Scorched) - Light-weight web framework for Ruby.
- [Firehose](http://firehose.io/) - Build realtime Ruby web applications. Created by the fine folks at Poll Everywhere.
- [Slanger](https://github.com/stevegraham/slanger) - Open Pusher implementation compatible with Pusher libraries.
- [render_sync](https://github.com/chrismccord/render_sync) - Real-time Rails Partials.
- [websocket-rails](https://github.com/websocket-rails/websocket-rails) - Plug and play websocket support for ruby on rails.

### Rust

- [Actix](https://actix.rs/docs/websockets) - A Rust web framework with support for the Websocket Protocol 
- [Websocket Core](https://github.com/bitwyre/websocket_core) - Rust Websocket server for periodic message broadcast
- [Tungstenite](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation
- [Tokio-Tungstenite](https://github.com/snapview/tokio-tungstenite) - Tokio binding for Tungstenite, the Lightweight stream-based WebSocket implementation
- [Fastwebsockets](https://github.com/denoland/fastwebsockets) - A fast RFC6455 WebSocket server implementation 
- [Ratchet](https://github.com/swimos/ratchet) - Ratchet is a fast, lightweight and fully asynchronous implementation of the WebSocket protocol with support for extensions and Deflate.
- [wtx](https://github.com/c410-f3r/wtx) - Client and server with encryption support.
- [async-tungstenite](https://github.com/sdroege/async-tungstenite) - Async binding for Tungstenite, runtime-agnostic across async-std, tokio, and smol.
- [rust-websocket](https://github.com/websockets-rs/rust-websocket) - RFC6455 library providing both synchronous and asynchronous client and server.
- [ntex](https://github.com/ntex-rs/ntex) - Powerful, pragmatic and fast web framework with WebSocket support.
- [tide-websockets](https://github.com/http-rs/tide-websockets) - WebSocket handler for the Tide web framework.

### Swift

- [Vapor](https://vapor.codes) - A high level web framework for Swift.
- [WebsocketKit](https://github.com/vapor/websocket-kit) - A low level WebSocket client library built on SwiftNIO.
- [Starscream](https://github.com/daltoniam/Starscream) - Conforming WebSocket (RFC 6455) client library in Swift for iOS and macOS.
- [SwiftNIO](https://github.com/apple/swift-nio) - Apple's cross-platform async event-driven network framework, a foundation for WebSocket servers.
- [Hummingbird](https://github.com/hummingbird-project/hummingbird) - Lightweight, flexible Swift server framework on SwiftNIO with WebSocket support.
- [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - Official Socket.IO client for Swift.

### Protocols and APIs

- [RFC6455](https://www.rfc-editor.org/rfc/rfc6455) - The WebSocket Protocol.
- [The WebSocket API](https://websockets.spec.whatwg.org) - WebSockets - Living Standard.
- [TikTool Live](https://tik.tools/docs) - Real-time TikTok LIVE stream events (chat, gifts, viewers) via WebSocket. SDKs for [Node.js](https://www.npmjs.com/package/tiktok-live-api) and [Python](https://pypi.org/project/tiktok-live-api/).


## Managed / Hosted Services

- [Ably](https://ably.com) - Managed pub/sub realtime platform with WebSocket-based messaging, presence, and guaranteed delivery.
- [Pusher Channels](https://pusher.com) - Hosted WebSocket API for pub/sub realtime features with client SDKs across platforms.
- [PubNub](https://www.pubnub.com) - Realtime edge messaging platform delivering pub/sub over WebSockets at global scale.
- [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) - Stateful serverless coordination primitive commonly used to build WebSocket rooms and realtime backends at the edge.
- [Cloudflare Workers WebSockets](https://developers.cloudflare.com/workers/runtime-apis/websockets/) - Native WebSocket support in Cloudflare Workers, including hibernatable connections.
- [AWS API Gateway WebSocket APIs](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html) - Managed WebSocket APIs that route messages to Lambda and other AWS backends.
- [PartyKit](https://github.com/partykit/partykit) - Open-source platform for building realtime multiplayer apps on Cloudflare with a batteries-included WebSocket server abstraction.
- [Liveblocks](https://www.liveblocks.io) - Hosted realtime collaboration infrastructure providing presence, storage, and comments over WebSockets.
- [Supabase Realtime](https://supabase.com/docs/guides/realtime) - Realtime engine broadcasting Postgres changes, presence, and messages to clients over WebSockets.
- [Momento Topics](https://www.gomomento.com) - Serverless pub/sub and caching service with realtime topics accessible over WebSockets.

## GUI Testing Tools

- [Firecamp](https://firecamp.io/websocket) - Full-featured GUI WebSocket testing client which helps Dev team to test WebSocket events visually. Test APIs, save them in the project and share it with your team. 
- [WebSocket King](https://websocketking.com) - A browser based WebSocket testing client that supports multiple simultanious connections, logs of incoming and outgoing messages, custom protocols and multiple projects.
- [Simple WebSocket Client](https://chrome.google.com/webstore/detail/simple-websocket-client/pfdhoblngboilpfeibdedpjgfnlcodoo) - Simple WebSocket Client (Chrome Extension).
- [Postman WebSocket](https://learning.postman.com/docs/sending-requests/websocket/create-a-websocket-request/) - Send and inspect raw WebSocket and Socket.IO requests inside Postman, with saved history and collections.
- [Hoppscotch Realtime](https://hoppscotch.io/realtime) - Free, open-source browser client for testing WebSocket, SSE, Socket.IO and MQTT connections.
- [Insomnia](https://insomnia.rest) - Open-source API client with native WebSocket request support alongside REST, GraphQL and gRPC.
- [Bruno](https://www.usebruno.com) - Open-source, offline-first API client with WebSocket support and git-friendly plain-text collections.
- [Apidog](https://apidog.com/websocket-testing/) - All-in-one API platform with a dedicated WebSocket debugging client for messages, params and auth.
- [Thunder Client](https://www.thunderclient.com) - Lightweight VS Code REST and WebSocket client for testing connections without leaving the editor.
- [WebSocket.in](https://www.websocket.in) - Browser-based WebSocket tester plus free public echo and broadcast endpoints for quick checks.

## Browser libraries

- [WSGO](https://github.com/melishev/wsgo) - like Axios.js, only for WebSocket, adds handy debugging tools 
- [ZilaWS Client](https://zilaws.com) - A very easy-to-use and fast WS implementation with async/await eventhandlers.
- [react-use-websocket](https://github.com/robtaussig/react-use-websocket) - React hook for WebSocket connections with reconnection, message queueing, and shared connections.

## Visualization Tools

- [Foxglove ws-protocol](https://github.com/foxglove/ws-protocol) - Websocket protocol for visualization of multimodal data.

## Command-Line Interface (CLI) Tools

- [claws](https://github.com/thehowl/claws) - Awesome WebSocket Client - an interactive command line client for testing websocket servers.
- [wscat](https://github.com/websockets/wscat) - WebSocket cat.
- [wsta](https://github.com/esphen/wsta) - A CLI development tool for WebSocket APIs.
- [ws](https://github.com/hashrocket/ws) - websocket command line tool.
- [wssh](https://github.com/progrium/wssh) - wssh ("wish") is a command-line utility/shell for WebSocket inspired by netcat.
- [wsc](https://github.com/raphael/wsc) - A tiny command line websocket client written in Go.
- [ws-cli](https://github.com/kseo/ws-cli) - WebSocket Command Line Client written in Go.
- [ws-tool](https://github.com/plantain-00/ws-tool) - A Develop Tool to Test WebSocket, Socket.IO, Stomp, Bayeux, HTTP, TCP, UDP, WebRTC, DNS API.
- [websocketd](https://github.com/joewalnes/websocketd) - Turn any program that uses STDIN/STDOUT into a WebSocket server. Like inetd, but for WebSockets.
- [websocat](https://github.com/vi/websocat) - Command-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.
- [iola](https://github.com/pvarentsov/iola) - Socket client with Rest API (WebSocket, Socket.IO, TCP, Unix socket).

## Real Life Stories

- [The top 10 realtime web apps](http://www.creativebloq.com/app-design/top-10-realtime-web-apps-5133752)
- [Super sync sports](https://blog.chromium.org/2013/02/on-track-with-chrome-super-sync-sports.html)
- [Kaazing](https://kaazing.com/)
- [Taskade](https://taskade.com) - Real-time collaborative task lists and outlines.

## Security

- [WebSockets - An Introduction](https://gist.github.com/subudeepak/9897212) - The problems and some security implications of websockets - Cross-site WebSockets Scripting (XSWS).
- [Hacking with WebSockets](https://media.blackhat.com/bh-us-12/Briefings/Shekyan/BH_US_12_Shekyan_Toukharian_Hacking_Websocket_Slides.pdf) - Talk on Blackhat USA 2012 Conference.
- [Testing for WebSockets Security Vulnerabilities](https://portswigger.net/web-security/websockets) - Interactive vulnerable WebSocket demos that provide hands-on learning of WebSocket security risks
- [Testing WebSockets](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/11-Client-side_Testing/10-Testing_WebSockets) - OWASP Web Security Testing Guide (WSTG), client-side WebSocket testing chapter.
- [Websockets Auth](http://stratumsecurity.ghost.io/2016/06/13/websockets-auth) - Journey into WebSockets Authentication/Authorization.
- [WebSocket Security](https://devcenter.heroku.com/articles/websocket-security) - The WebSocket protocol is a young technology, and brings with it some risks. Decades of experience have taught the web community some best practices around HTTP security, but the security best practices in the WebSocket world aren’t firmly established, and continue to evolve. Nevertheless, some themes have emerged and they are described in this article.
- [Cross-Site WebSocket Hijacking](http://www.christian-schneider.net/CrossSiteWebSocketHijacking.html) - Cross-Site WebSocket Hijacking (CSWSH) - Web Application Security Blog.
- [Cross-site WebSocket hijacking labs](https://portswigger.net/web-security/websockets/cross-site-websocket-hijacking) - PortSwigger deep-dive on CSWSH with interactive labs.

## Theory

### Articles & Papers

- [An introduction to Websockets](http://blog.teamtreehouse.com/an-introduction-to-websockets) - Brief History of Real-Time Web Applications.
- [Introducing WebSockets: Bringing Sockets to the Web](https://www.html5rocks.com/en/tutorials/websockets/basics/) - The Problem: Low Latency Client-Server and Server-Client Connections.
- [About HTML5 WebSocket](https://websocket.org/aboutwebsocket.html) - About HTML5 WebSocket.
- [Node.js WebSocket](https://medium.com/@denizozger/finding-the-right-node-js-websocket-implementation-b63bfca0539#.q2313as8p) - Finding the right Node.js WebSocket implementation.
- [Websockets 101](http://lucumr.pocoo.org/2012/9/24/websockets-101/) - Armin Ronacher's Thoughts and Writings (creator of Flask).
- [Real-time Apps](https://www.sitepoint.com/real-time-apps-websockets-server-sent-events/) - Building Real-time Apps with Websockets & Server-Sent Events.
- [Real-Time Web by Paul Banks](https://banksco.de/p/state-of-realtime-web-2016.html) - The State of Real-Time Web in 2016.
- [Are WebSockets the future?](https://samsaffron.com/archive/2015/12/29/websockets-caution-required) - WebSockets, caution required!
- [MSDN Microsoft Blog](https://msdn.microsoft.com/en-us/hh563510.aspx) - The Dangers of HTML5: WebSockets and Stable Standards.
- [Webpush Internet-Draft](https://martinthomson.github.io/drafts/draft-thomson-webpush-http2.html) - Generic Event Delivery Using HTTP Push.
- [Full Stack Python](https://www.fullstackpython.com/websockets.html) - WebSockets on Python.
- [Do you really need WebSockets?](https://blog.stanko.io/do-you-really-need-websockets-343aed40aa9b) - WebSockets explanation.

### Tutorials

- [Honeybadger.IO](http://blog.honeybadger.io/building-a-simple-websockets-server-from-scratch-in-ruby) - Building a simple websockets server from scratch in Ruby.
- [David Walsh](https://davidwalsh.name/websocket) - WebSocket and Socket.IO.
- [Implementing a WebSocket server with Node.js](https://medium.com/hackernoon/implementing-a-websocket-server-with-node-js-d9b78ec5ffa8).
- [Lostmoa](https://lostmoa.com/tags/websocket/) - A collection of Django Channels WebSocket tutorials. 
- [GeniePy](https://geniepy.com/blog/how-to-set-up-websockets-in-starlette/) - How to set up WebSockets in Starlette
- [Writing WebSocket servers (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_servers) - MDN guide to implementing the server side of the WebSocket protocol from scratch.
- [Writing WebSocket client applications (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_client_applications) - MDN reference for building browser WebSocket clients.
- [WebSocket (javascript.info)](https://javascript.info/websocket) - Clear, modern chapter on the browser WebSocket API with runnable examples.
- [Using WebSockets on Cloudflare Workers](https://developers.cloudflare.com/workers/examples/websockets/) - Official docs and example for handling WebSockets at the edge.


### Books

- [WebSocket](https://www.oreilly.com/library/view/~/9781449369262/) - Lightweight Client-Server Communications. Andrew Lombardi.
- [The Definitive Guide to HTML5 WebSocket](http://www.apress.com/gp/book/9781430247401) - Build Real-Time Applications with HTML5. By Vanessa Wang, Frank Salim, and Peter Moskovits. Source Code [here](https://github.com/Apress/def-guide-to-html5-websocket).
- [High Performance Browser Networking](https://hpbn.co/websocket/) - High Performance
Browser Networking: WebSocket.

### Sites

- [WebSocket ORG](https://websocket.org) - The one-stop-shop for all your websocket needs.
- [WebSockets MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) - WebSockets Mozilla Developer Network (MDN).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/facundofarias/awesome-websockets/blob/master/CONTRIBUTING.md) before submitting your suggestion.

Feel free to [open an issue](https://github.com/facundofarias/awesome-websockets/issues) or [create a pull request](https://github.com/facundofarias/awesome-websockets/pulls) with your additions.

Thanks!

## Acknowledgments

Table of contents generated with [DocToc](https://github.com/thlorenz/doctoc)
