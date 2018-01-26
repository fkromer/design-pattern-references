---
layout: post
title: "Circuit Breaker"
categories: ['software', 'microservice']
---

Application Patterns - Reliability Patterns

How to prevent a network or service failure from cascading to other services?
Invoke a remote service via a proxy that fails immediately when the failure rate
of the remote call exceeds a threshold.

[microservices.io - Microservice Patterns - Circuit Breaker](http://microservices.io/patterns/reliability/circuit-breaker.html)
