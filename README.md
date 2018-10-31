# SpringCloud-Feign-Consul_Demo

1. 通过将consul作为注册中心，通过两个服务提供方（consul1和consul）在注册中心进行注册，提供hello接口服务；    
2. 通过customer作为服务使用方，远程调用hello方法；    
3. 两个服务会交替提供服务，说明两个服务中心自动提供了服务均衡负载的功能。如果我们将服务提供者的数量在提高为N个，测试结果一样，请求会自动轮询到每个服务端来处理。    

[参考链接](http://www.ityouknow.com/spring-cloud.html)
