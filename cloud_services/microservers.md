# 微服务

使用微信云托管部署。

## 划分

大体遵循一个子应用对应一个微服务的原则，允许子应用有多个微服务。比如，量潮课堂有主站和管理后台两个子应用，分别有对应的主要微服务，同时主站还有代码执行器微服务支持。

每个微服务使用一个子域名。暂时使用微信云托管默认域名。
计划购买`quanttideapi.com`并制定域名分配规则。
原定`api.quanttide.com`或者`api.<service>.quanttide.com`计划取消。

## 编排和治理

计划使用腾讯云微服务引擎北极星。

![](images/orchestration.jpeg)

（2022-10-22：旧图。）
