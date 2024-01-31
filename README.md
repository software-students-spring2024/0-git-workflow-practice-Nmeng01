# Git Practice

https://grpc.io/docs/what-is-grpc/introduction/

Over winter break, I started on an open-source project with a family friend. We are trying to benchmark the speeds of gRPC and REST API architectures. Most of this stuff was new to me so I had to do a lot of research, particularly on gRPC since it is quite new, so I used this article to help me understand gRPC better and how it differs from REST. I learned that gRPC takes advantage of the protobuf data format as opposed to REST which uses JSON. The client-server interactions can be much quicker as a result since protobuf utilizes a binary message format, whereas JSON uses text. I also learned that converting one's projects to utilize gRPC can be a pain because one has to rewrite a lot of their data infrastructure, which could lead to further errors and generally cause a lot of hassle. This is why we wanted to benchmark gRPC vs. REST: if there are scenarios where REST is maybe 80% as fast as gRPC, it might not be worth it to uproot one's entire project for the sake of 20% more speed.




I feel that the information in this article is very sophisticated as I'm unfamiliar with Protocol Buffers. In what scenarios would it be better to use gPRC over other API architechtures? I wonder if it would provide more security since it encodes in binary. 
-Natalie Wu