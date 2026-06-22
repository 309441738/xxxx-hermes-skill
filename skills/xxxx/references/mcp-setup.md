# MCP 配置（Hermes Agent）

在 `~/.hermes/config.yaml` 中添加：

```yaml
mcp_servers:
  xxxx:
    transport: streamable-http
    url: http://127.0.0.1:3004/api/gw/mcp/5c11491b-fd3c-4727-8c5c-1501899717a5
```

或使用 CLI：`hermes mcp install` 浏览 catalog 后手动配置 remote URL。
