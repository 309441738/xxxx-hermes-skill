# MCP 配置（Hermes Agent）

在 `~/.hermes/config.yaml` 中添加：

```yaml
mcp_servers:
  xxxx:
    transport: streamable-http
    url: http://127.0.0.1:3004/api/gw/mcp/239b8089-7f92-431f-acf4-dfd18d2c0865
```

或使用 CLI：`hermes mcp install` 浏览 catalog 后手动配置 remote URL。
