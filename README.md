# Microservice.PoC.Steeltoe

## Steeltoe

[![N|Steeltoe](https://www.cnblogs.com/images/cnblogs_com/edisonchou/1260867/o_logo-banner.PNG)](http://steeltoe.io/)
Steeltoe is an open source project that enables .NET developers to implement industry standard best practices when building resilient microservices for the cloud. The Steeltoe client libraries enable .NET Core and .NET Framework apps to easily leverage Netflix Eureka, Hystrix, Spring Cloud Config Server, and Cloud Foundry services.
For more details, please read this => (http://steeltoe.io/)
What's more, Pivotal provide a sample application on Github => (https://github.com/SteeltoeOSS/Samples/tree/master)

Steeltoe enable .NET/.NET Core to use the below components at this moment:
  - Service Discovery
  - Config Server
  - Circuit Breaker
  - Cloud Connectors

## About this sample

[![N|ASP.NET Core](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1536848117066&di=f167c5db2797e829e063e2cef2237e29&imgtype=0&src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fimages%2F20170926%2F8543d771f7fe420a897e1573e35d02c2.png)](https://docs.microsoft.com/zh-cn/aspnet/core/getting-started/?view=aspnetcore-2.1&tabs=windows)
This sample is a microservice project developed by ASP.Net Core with Spring Cloud based on Steeltoe.

## Installation

To use Steeltoe, we can use the below NuGet packages:
Steeltoe Common Library
```sh
PM> Install-Package Steeltoe.Common
```
Steeltoe Service Discovery Client
```sh
PM> Install-Package Steeltoe.Discovery.Client 
```


## Rerference

Find more : http://edisonchou.cnblogs.com