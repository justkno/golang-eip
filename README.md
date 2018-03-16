# Enterprise Integration Patterns for Go

## What is golang-eip?

This library is a (work in progress) implementation of the book [Enterprise Integration Patterns](http://www.enterpriseintegrationpatterns.com/)
by Gregor Hohpe and Bobby Woolf.

It takes inspiration from the [Apache Camel] (http://camel.apache.org/) framework.  

## Why are you writing this library?

"The thing that hath been, it is that which shall be; and that which is done is that which shall be done: and there is no new thing under the sun." (KJV, Ecc 1.9)

Every software developer knows their fundamental algorithms and data structures by heart. Hash tables and quick sort haven't changed much in the last forty years.
These form a common language that we use to propose and develop solutions with one another.

While most engineers are loathe to re-invent the wheel at the level of fundamentals (at whatever level they think fundamentals bottom out),
they love to re-invent the wheel at the level of inter-service communication. Because they lack a shared language for describing messaging
within and between services, the result is often a tangled, brittle, high-touch, mess that becomes exponentially harder to improve as
complexity increases.

A surprising number of these communication patterns can be replaced with a message bus.

EIP presents a language to describe message buses within and between applications. Consumers, Producers, Routes, Messages, Transformers and the like
form a foundation for describing solutions that have been reinvented in thousands of companies tens of thousands of times.

I love Golang, and I think it's an excellent language in which to implement a performant message bus.
