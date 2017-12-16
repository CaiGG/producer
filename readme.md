### Eureka Provider 服务提供

eureka的基本架构，由3个角色组成：

1. Eureka Server
   * 提供服务注册和发现
2. Service Provider
   * 服务提供方
   * 将吱声服务注册到Eureka，从而是服务消费方能够找到
3. Service Consumer
   * 服务消费方
   * 从Eureka 获取注册服务列表，从而能够消费服务。

