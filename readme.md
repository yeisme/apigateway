# apigateway

apigateway 负责管理 API 网关的配置和路由规则，apigateway 服务定位为一个集中式的安全和策略执行点，负责处理认证并将可信的用户身份信息传递给下游，而让下游服务专注于纯粹的业务逻辑

```txt
X-User-ID: 12345
X-User-Name: alice
X-User-Roles: admin,reader
```
