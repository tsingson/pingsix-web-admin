# pingsix-web-admin

a go backend via grpc + [connectrpc](https://github.com/connectrpc) + react ( typescript) for [PingSix](https://github.com/zhu327/pingsix) 


## what

[PingSix](https://github.com/zhu327/pingsix) is a high-performance and scalable API gateway tailored for modern cloud-native environments, 
build with  [Cloudflare's Pingora](https://github.com/cloudflare/pingora) and Inspired by [ApacheAPISIX](https://apisix.apache.org/).

we use PingSix in our demo project.  and we use go backend via grpc + connectrpc + react ( typescript) for web adminitrator panel.

so, we re-use our web admin code base again for PingSix admin panel.

## why

[connectrpc](https://github.com/connectrpc) is grpc that easy to use and full support google gRPC, and provide a [connect-es](https://github.com/connectrpc/connect-es) that easy to work with react web with grpc mode.



## design

react web ( connectrpc-es) <--(grpc)-->  go backend <---( grpc )---> rust ( admin ) <-(uds)-> pingsix ( api gateway)






## notice

this is a WIP ptototype project for demo only.

