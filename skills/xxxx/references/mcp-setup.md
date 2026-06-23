# MCP 配置（Hermes Agent）

在 `~/.hermes/config.yaml` 中添加：

```yaml
mcp_servers:
  xxxx:
    transport: streamable-http
    url: http://127.0.0.1:3004/api/gw/mcp/d645c4ca-43b9-4d50-991d-ce48512c2da8
```

或使用 CLI：`hermes mcp install` 浏览 catalog 后手动配置 remote URL。
