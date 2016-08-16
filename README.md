This demonstrates the problem of Eureka dashboard not serving static resources (i.e. /eureka/css/wro.css and eureka/js/wro.js) 
when you annotate bootstrap app class with both  @EnableConfigServer and @EnableEurekaServer.

The bug has been reported as [https://github.com/spring-cloud/spring-cloud-netflix/issues/1262](https://github.com/spring-cloud/spring-cloud-netflix/issues/1262)
