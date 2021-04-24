# 服务端测试

注意贯彻云原生的“反脆弱”原则，为开发者提供可靠的测试方案。

## 性能/压力/负载测试

概念详见：https://www.huaweicloud.com/articles/c9c95eea7685c4481264753d85113bd7.html。

### 扩缩容能力测试

TODO：
- 以Django服务最大可以承受多大访问量？需不需要优化Django？
- 需不需要多个云托管版本测试不同设置下的承压能力？如何配置高可用或者低成本的云托管实例数量？
- 如果业务实际出现异常，如何区分业务逻辑和云服务框架的问题？