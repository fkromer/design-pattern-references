---
layout: post
title: "Distributed Tracing"
categories: ['software', 'microservice']
---

Application Infrastructure Patterns - Obsevability Patterns

How to understand the behavior of an application and troubleshoot problems?
Instrument services with code that assigns each external request an unique
identifier that is passed between services. Record information (e.g. start time,
end time) about the work (e.g. service requests) performed when handling the
external request in a centralized service.

([Microservice Patterns - Distributed Tracing](http://microservices.io/patterns/observability/distributed-tracing.html))
