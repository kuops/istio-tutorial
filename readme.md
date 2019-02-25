# Java (Spring Boot, Vert.x and Microprofile) + Istio on Kubernetes

redhat 的 java istio demo 演示服务

三个微服务的依赖关系

```
customer → preference → recommendation
```



[1.环境准备](documentation/modules/ROOT/pages/1setup.adoc)

[2.部署微服务](documentation/modules/ROOT/pages/2deploy-microservices.adoc)

[3.监控和跟踪](documentation/modules/ROOT/pages/3monitoring-tracing.adoc)

[4.简单的路由](documentation/modules/ROOT/pages/4simple-routerules.adoc)

[5.高级路由](documentation/modules/ROOT/pages/4advanced-routerules.adoc)

include::documentation/modules/ROOT/pages/6fault-injection.adoc[]

include::documentation/modules/ROOT/pages/7circuit-breaker.adoc[]

include::documentation/modules/ROOT/pages/8egress.adoc[]

== Advanced use cases

include::documentation/modules/advanced/pages/kiali.adoc[]

include::documentation/modules/advanced/pages/virtualization.adoc[]

include::documentation/modules/advanced/pages/mTLS.adoc[]

== Tips &amp; Tricks

include::documentation/modules/ROOT/pages/9tips.adoc[]

