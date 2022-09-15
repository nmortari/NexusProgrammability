# gNMI Overview

## About gRPC
gNMI is built on top of Google Remote Procedure Call (gRPC). gRPC is an open source high performance RPC framework released in 2016. It uses HTTP/2 for transport, protocol buffers for the interface description language, and includes the following features:

* authentication
* bi-directional streaming
* bi-direction flow control
* blocking bindings
* non-blocking bindings
* cancellation
* timeouts

gRPC can generate cross-platform client and server bindings for many languages. It also supports TLS and token-based authentication. gRPC uses protocol buffers to encode data.

## About gNMI
gRPC Network Management Interface (gNMI) is a specification of RPCs for managing or collecting the state of a device. The content provided through gNMI can be modeled using YANG. gRPC carries gNMI and provides the ability to create and transmit requests.

## NX-OS gNMI Features
gNMI can be transmitted in two ways:

* Dial-In
    * In this mode, the client will initiate the connection to the switch.
* Dial-Out
    * In this mode, the switch will initiate the connection to the client.

