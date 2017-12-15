# awesome-microservice
A curated list of Microservice resources

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.
## Philosophy of  Microservice

### Origin of Microservice

* [Microservices from Martin Fowler](http://martinfowler.com/articles/microservices.html)
* [Microservices from Martin Fowler In Chinese](http://blog.csdn.net/wurenhai/article/details/37659335)


### Architectural Patterns(similar to book software-architecture-patterns from O`REILLY )

#### Core patterns

* [Monolithic architecture from Chris Richardson](http://microservices.io/patterns/monolithic.html)
* [Microservices architecture from Chris Richardson](http://microservices.io/patterns/microservices.html)
* [API Gateway from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Bounded Context from Martin Fowler](http://martinfowler.com/bliki/BoundedContext.html)
* [Circuit Breaker from Martin Fowler](http://martinfowler.com/bliki/CircuitBreaker.html)
* [Circuit Breaker ~ netflix](http://doc.akka.io/docs/akka/snapshot/common/circuitbreaker.html)

#### Deployment patterns

* [Multiple service instances per host](http://microservices.io/patterns/deployment/multiple-services-per-host.html)
* [Service instance per host](http://microservices.io/patterns/deployment/single-service-per-host.html)
* [Service instance per VM](http://microservices.io/patterns/deployment/service-per-vm.html)
* [Service instance per Container](http://microservices.io/patterns/deployment/service-per-container.html)

#### Service discovery


* [Client-side discovery from Chris Richardson](http://microservices.io/patterns/client-side-discovery.html)
* [Server-side discovery from Chris Richardson ](http://microservices.io/patterns/apigateway.html)
* [Service registry from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Self registration from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [3rd party registration from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Service discovery with consul & etcd](https://aws.amazon.com/blogs/compute/service-discovery-via-consul-with-amazon-ecs/)



### Debates between advantage and disvantage

* [ PaaS vs. IaaS for Microservices Architectures: Top 6 Differences](http://blog.altoros.com/microservices-architectures-paas-vs-iaas-top-6-differences.html)
* [PaaS与IaaS 在微服务架构实现方面的6大不同  PaaS vs. IaaS for Microservices Architectures: Top 6 Differences in Chinese](http://weibo.com/p/1001603827173176797988)
* [ O’Reilly Software Architecture Conference大会上对微服务架构的探讨总结](http://radar.oreilly.com/2015/04/4-reasons-why-microservices-resonate.html)
* [Microservices Are Not a free lunch!](http://contino.co.uk/microservices-not-a-free-lunch/)
* [The Hidden Costs of Microservices by Justin Leitgeb](http://www.stackbuilders.com/news/the-hidden-costs-of-microservices)


## Books About Microservice

* [Antifragile: Things That Gain from Disorder](http://www.amazon.com/gp/product/0812979680)
* [The Black Swan](http://www.amazon.com/The-Black-Swan-Improbable-Robustness/dp/081297381X)
* [Implementing Domain-Driven Design](http://www.amazon.co.uk/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
* [Building Micro Services - Sam Newman](http://www.amazon.co.uk/Building-Microservices-Sam-Newman/dp/1491950358)
* [Building Micro Services - Sam Newman Downloadable preview edition](http://nginx.com/wp-content/uploads/2015/01/Building_Microservices_Nginx.pdf)
* [Antifragile Software - Russ Miles](https://leanpub.com/antifragilesoftware)
* [software-architecture-patterns from O`REILLY in English](http://www.oreilly.com/programming/free/files/software-architecture-patterns.pdf)
* [software-architecture-patterns from O`REILLY in Chinese](https://raw.githubusercontent.com/bboyfeiyu/android-tech-frontier/master/software-architecture-patterns/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E6%A8%A1%E5%BC%8F.pdf)
* [Production Ready Microservices - Susan J. Fowler](http://shop.oreilly.com/product/0636920053675.do)
* [Microservices in Production - Susan J. Fowler (free ebook)](http://www.oreilly.com/programming/free/microservices-in-production.csp)
* [Microservices with Docker, Flask, and React - Michael Herman](https://testdriven.io/)

## Online Videos and Presentations

* [Microservices - Martin Fowler](https://www.youtube.com/watch?v=wgdBVIX9ifA)
* [State of the Art in Microservices - Adrian Cockcroft](https://www.youtube.com/watch?v=nMTaS07i3jk)
* [Deploying And Testing Microservices - Sam Newman](https://www.youtube.com/watch?v=FotoHYyY8Bo)
* [Microservices Anti-Patterns](https://www.youtube.com/watch?v=I56HzTKvZKc)
* [Practical Considerations For Microservice Architectures - Sam Newman](https://www.youtube.com/watch?v=5NOaUK74Jt4)
* [Migrating to Microservices - Adrian Cockcroft](http://www.infoq.com/presentations/migration-cloud-native)
* [Microservices at Netflix](https://www.youtube.com/watch?v=LEcdWVfbHvc)
* [Microservices: Adaptive Systems for Innovative Organizations](https://www.youtube.com/watch?v=GDVcUM5wbxU)
* [Pros and Cons of a MicroServices Architecture talk at AWS ReInvent](http://www.slideshare.net/stonse/pros-and-cons-of-a-microservices-architecture-talk-at-aws-reinvent)
* [Chris Richardson: Developing event-driven microservices with event sourcing and CQRS](https://www.youtube.com/watch?v=9XhBPFjD0hw)
* [微服务  在InfoQ上的内容](http://www.infoq.com/cn/microservice)
* [Microservices  on  InfoQ website](http://www.infoq.com/cn/microservice)

## Events

## Best Practises from Industry

### Articles and Blogs

* [ service principles from Yelp-A guide to service principles at Yelp for our service oriented architecture](https://github.com/Yelp/service-principles)
* [Adopting Microservices at Netflix serial 1: It’s Time to Move to a Four-Tier Application Architecture](http://nginx.com/blog/time-to-move-to-a-four-tier-application-architecture/)
* [第一部分：是时候转移到四层架构上来了/](https://github.com/wanghaisheng/wanghaisheng.github.io/issues/65)
*  [Adopting Microservices at Netflix serial 2: Adopting Microservices at Netflix: Lessons for Architectural Design](http://nginx.com/blog/microservices-at-netflix-architectural-best-practices/)
* [第二部分：微服务架构在Netflix的应用：架构设计的经验教训](https://github.com/wanghaisheng/wanghaisheng.github.io/issues/65)
* [Adopting Microservices at Netflix serial 3: Adopting Microservices at Netflix: Lessons for Team and Process Design ](http://nginx.com/blog/adopting-microservices-at-netflix-lessons-for-team-and-process-design/)
* [第三部分：微服务架构在Netflix的应用：团队和流程设计相关的经验教训]()
* [Microservices - A Reality Check(point)by Andrew Harmel-Law — on Development, Microservices, Java, Camel, NetflixOSS, Spring 17 Oct 2014](http://capgemini.github.io/architecture/microservices-reality-check/)
*   [Idempotency is not a Medical Condition - Pat Helland](http://queue.acm.org/detail.cfm?id=2187821)
*   [Martin Fowler - You Must Be This Tall To Use Microservices](http://martinfowler.com/bliki/MicroservicePrerequisites.html)
*   [Adrian Cockroft - Migrating to Microservices](http://qconlondon.com/dl/qcon-london-2014/slides/AdrianCockcroft_MigratingToMicroservices.pdf)
*   [Michael Nygaard - Stability Patterns, and Ant-Patterns…](http://www.slideshare.net/justindorfman/stability-patterns-presentation)
*   [Eric Evans - Domain Driven Design: Tackling Complexity in the Heart of Software](http://www.amazon.co.uk/Domain-driven-Design-Tackling-Complexity-Software/dp/0321125215)
*   [Uncle Bob - Microservices and Jars](http://blog.cleancoder.com/uncle-bob/2014/09/19/MicroServicesAndJars.html)
*   [Steve Jones - Microservices - Money for old rope or re-badging SOA for the cool kids](http://service-architecture.blogspot.co.uk/2014/03/microservices-money-for-old-rope-or-re.html)
*   [Sonu K. Meena - How to build microservice?](https://www.linkedin.com/pulse/how-build-microservice-sonu-meena)
*	[Introduction to Microservices](http://nginx.com/blog/introduction-to-microservices/)
*	[微服务实战（一）：微服务架构的优势与不足](http://dockone.io/article/394)
*	[Building Microservices: Using an API Gateway ](http://nginx.com/blog/building-microservices-using-an-api-gateway/)
*	[微服务实战（二）：使用API Gateway](http://dockone.io/article/482)
*   [Building Microservices: Inter-Process Communication in a Microservices Architecture](https://www.nginx.com/blog/building-microservices-inter-process-communication/)
*   [微服务实战（三）：深入微服务架构的进程间通信](http://dockone.io/article/549)
*	[微服务实战（四）：服务发现的可行方案以及实践案例](http://dockone.io/article/771)
*	[Service Discovery in a Microservices Architecture ](https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/)
*	[Event-Driven Data Management for Microservices](https://www.nginx.com/blog/event-driven-data-management-microservices/)
*	[微服务实践（五）：微服务的事件驱动数据管理](http://dockone.io/article/936)
*	[0 to Microservice in 5 minutes with Go, go-microservice-template and Minke](http://nicholasjackson.github.io/microservices/go/building-and-testing-microservices-part1/)
*	[5分钟学习基于Go，go-microservice-template，Minke的微服务](http://dockone.io/article/1117)
*	[IS REST BEST IN A MICROSERVICES ARCHITECTURE?](http://capgemini.github.io/architecture/is-rest-best-microservices/)
*	[REST真的完全适合微服务架构吗？](http://dockone.io/article/952)
*	[ Microservice架构模式简介 ](http://www.cnblogs.com/loveis715/p/4644266.html)
*	[单元化与分布式架构的切分问题](http://timyang.net/architecture/cell-distributed-system/)
*	[ 一个单元化架构的例子](http://mp.weixin.qq.com/s?__biz=MzI5MDE1NjkyNw==&mid=409213079&idx=1&sn=55326805b08b84d86c4e02bc405d0bbe&scene=2&srcid=041143B6BQTKvXlHVsDGbN1V&from=timeline&isappinstalled=0#wechat_redirect)
*	[ Microservice微服务架构两年来在京东咚咚从理论到落地的实践总结](http://mp.weixin.qq.com/s?__biz=MzAxMTEyOTQ5OQ==&mid=2650610530&idx=1&sn=acd24986fe42181fcd81496f7a922f33&scene=0#wechat_redirect)


### Example Projects

* [Chris Richardson has published the example code for his QCONSF talk on building event-driven microservices. The example microservices-based application is built using event sourcing and command query responsibility separation (CQRS). There are currently two versions of the application - Scala/Spring and Java/Spring - with others to follow. Take a look!](https://github.com/cer/event-sourcing-examples)
* [Building Microservices with Open Source Technologies by Suresh Balla](http://www.developer.com/open/building-microservices-with-open-source-technologies.html)
* [如何做实时监控？—— 参考 Spring Boot 实现](http://www.juvenxu.com/2014/12/09/real-time-monitoring-with-spring-boot/)
* [ 深入学习微框架：Spring Boot ](http://www.infoq.com/cn/articles/microframeworks1-spring-boot)
* [NetflixOSS Acme Air Sample and Benchmark](https://github.com/aspyker/acmeair-netflix/tree/astyanax)
* [ Experiments With Docker For Acme Air Dev](http://ispyker.blogspot.tw/2014/01/experiments-with-docker-for-acme-air-dev.html)
* [CRUD using Spring Data Rest and AngularJS using Spring Boot](http://www.programming-free.com/2014/07/spring-data-rest-with-angularjs-crud.html)
* [ microservice of convert html to pdf](https://github.com/shouldbee/docker-html2pdf)
* [ Microservices tests with RabbitMQ and Docker](https://github.com/codescrum/microservice-tests-01)
* [ A demonstration of a Microservices architecture using Spring Boot, Docker and Fig.](https://github.com/boonen/microservices-demo)
* [ Experiments with microservices and Docker](https://github.com/mboeh/oignon-exp)
* [ Example code for my building and deploying microservices with event sourcing, CQRS and Docker presentation](https://github.com/cer/event-sourcing-examples)
* [ Some idea of how micro-services can be handled using SkyDNS, SkyDock and Docker](https://github.com/criolit/docker-microservices)
* [ This is a presentation on Docker held at FINN Architecture Summit - Service Orientation on 2015.01.21.](https://github.com/finn-no/Docker-and-Microservices)
* [ Dummy project to try out new tools for me like Docker and RabbitMQ](https://github.com/jordi-chacon/dummy-dockerized-microservices)
* [ OAuth2 authentication server designed to work in a docker-based microservices architecture.](https://github.com/nielskrijger/auth-server)

### Library and Tools



## People

* James Lewis
* Sam Newman
* Russ Miles
* Martin Fowler
* Chris Richardson
* Daniel Woods

## Discussion Group

* [Join the microservices google group](https://groups.google.com/forum/#!forum/microservices)


Many thanks to [Owain Lewis](https://github.com/owainlewis/microservice-design)
and [Chris Richardson](http://microservices.io/index.html) [i5ting](https://github.com/i5ting)
