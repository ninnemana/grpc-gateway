# grpc-gateway

[![CircleCI](https://circleci.com/gh/ninnemana/grpc-gateway.svg?style=svg)](https://circleci.com/gh/ninnemana/grpc-gateway)

grpc-gateway is a plugin of [protoc](http://github.com/google/protobuf).
It reads [gRPC](http://github.com/grpc/grpc-common) service definition,
and generates a reverse-proxy server which translates a RESTful JSON API into gRPC.
This server is generated according to [custom options](https://cloud.google.com/service-management/reference/rpc/google.api#http) in your gRPC definition.

It helps you to provide your APIs in both gRPC and RESTful style at the same time.

![architecture introduction diagram](https://docs.google.com/drawings/d/12hp4CPqrNPFhattL_cIoJptFvlAqm5wLQ0ggqI5mkCg/pub?w=749&amp;h=370)

To learn more about us check out our documentation on:

*   [Our background](_docs/background.md)
*   [Installation and usage](_docs/usage.md)
*   [Examples](_docs/examples.md)
*   [Features](_docs/features.md)
*   [AWS API Gateway tips](_docs/aws.md)


# Contribution
See [CONTRIBUTING.md](http://github.com/ninnemana/grpc-gateway/blob/master/CONTRIBUTING.md).

# License
grpc-gateway is licensed under the BSD 3-Clause License.
See [LICENSE.txt](https://github.com/ninnemana/grpc-gateway/blob/master/LICENSE.txt) for more details.
