### CircuitBreaker
[hystrix-javanica](https://github.com/Netflix/Hystrix/tree/master/hystrix-contrib/hystrix-javanica) ：Spring CircuitBreaker应该用的就是这个。基于Annotation，无需写HystrixCommand类

### AOP
by Justin Wilson

- [Aspect-Oriented Programming in Spring Boot Part 1: Making Your Own Hystrix Aspect](https://www.credera.com/blog/technology-insights/open-source-technology-insights/aspect-oriented-programming-in-spring-boot-part-1-making-your-own-hystrix-aspect/)

- [Aspect-Oriented Programming in Spring Boot Part 2: Spring JDK Proxies vs CGLIB vs AspectJ](https://www.credera.com/blog/technology-insights/open-source-technology-insights/aspect-oriented-programming-in-spring-boot-part-2-spring-jdk-proxies-vs-cglib-vs-aspectj/)

- [Aspect-Oriented Programming in Spring Boot Part 3: Setting up AspectJ Load-Time Weaving](https://www.credera.com/blog/technology-insights/open-source-technology-insights/aspect-oriented-programming-in-spring-boot-part-3-setting-up-aspectj-load-time-weaving/)

#### Retry
- [spring-retry](https://github.com/spring-projects/spring-retry) : Declarative retry support for Spring applications. Use @Retryable annotation attributes for including and excluding exception types, limiting the number of retries and the policy for backoff.

- [jcabi-aspects - @RetryOnFailure](http://aspects.jcabi.com/) : Useful Java AOP Aspects is a collection of useful AOP aspects and Java annotations which allow you to modify the behavior of your Java application without writing lots of duplicate code.