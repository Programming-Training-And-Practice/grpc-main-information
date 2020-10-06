# gRPC.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [protobuf.](https://github.com/descriptions-of-it-technologies/protobuf)
* [Pros.](#pros)
* [Const.](#cons)
* [Type of gRPC.](#types-of-grpc)
* [Scalability.](#scalability)
* [Help](#help)





## About.





## Documentation.
* [gRPC](https://grpc.io/)
* [reactive-gRPC]()





## Pros.
* Payload Size.
* Build on top of HTTP/2.
* Efficient use of resources.
* Simplicity in Development.
* Wide support.
* Hig performance.
* Easy to build API with ProtoBuf.
* Performance 
* gRPC-web is ugly.
* Have Back Pressure. "Yeah... you have... but... not really"





## Cons.
* Unclear API.
* No Backpressure support.
* Just a wrapper on top HTTP/2.
* gRPC-web. No native browser support.
* Proxies.





## Types of gRPC.
* Unary.
* Client Streaming.
* Server Streaming.
* Bidirectional Streaming.





## Scalability.
Server.
* gRPC Server are asynchronous by default. This means they do not block threads on request.
* Therefore each gRPC server can serve millions of requests in parallel. 

Clients.
* gRPC Clients can be asynchronous or synchronous(blocking).
* The Client decides which model works best for the performance needs.
* gRPC Clients can perform client side load balancing.




## Help.
